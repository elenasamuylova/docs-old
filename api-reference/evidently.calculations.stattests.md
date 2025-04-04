# evidently.calculations.stattests package

Available statistical tests.
For detailed information about statistical tests see module documentation.

## Submodules

## <a name="module-evidently.calculations.stattests.anderson_darling_stattest"></a>anderson_darling_stattest module

Anderson-Darling test of two samples.

Name: “anderson”

Import:

```python
>>> from evidently.calculations.stattests import anderson_darling_test
```

Properties:
- only for numerical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import anderson_darling_test
>>> options = DataDriftOptions(all_features_stattest=anderson_darling_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="anderson")
```

## <a name="module-evidently.calculations.stattests.chisquare_stattest"></a>chisquare_stattest module

Chisquare test of two samples.

Name: “chisquare”

Import:

```python
>>> from evidently.calculations.stattests import chi_stat_test
```

Properties:
- only for categorical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import chi_stat_test
>>> options = DataDriftOptions(all_features_stattest=chi_stat_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="chisquare")
```

## <a name="module-evidently.calculations.stattests.cramer_von_mises_stattest"></a>cramer_von_mises_stattest module

Cramer-Von-mises test of two samples.

Name: “cramer_von_mises”

Import:

```python
>>> from evidently.calculations.stattests import cramer_von_mises
```

Properties:
- only for numerical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import cramer_von_mises
>>> options = DataDriftOptions(all_features_stattest=cramer_von_mises)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="cramer_von_mises")
```


### class CramerVonMisesResult(statistic, pvalue)
Bases: `object`

## <a name="module-evidently.calculations.stattests.energy_distance"></a>energy_distance module

Energy-distance test of two samples.

Name: “ed”

Import:

```python
>>> from evidently.calculations.stattests import energy_dist_test
```

Properties:
- only for numerical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import energy_dist_test
>>> options = DataDriftOptions(all_features_stattest=energy_dist_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="ed")
```

## <a name="module-evidently.calculations.stattests.epps_singleton_stattest"></a>epps_singleton_stattest module

Epps-Singleton test of two samples.

Name: “es”

Import:

```python
>>> from evidently.calculations.stattests import epps_singleton_test
```

Properties:
- only for numerical features
- returns p-value
- default threshold 0.05

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import epps_singleton_test
>>> options = DataDriftOptions(all_features_stattest=epps_singleton_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="es")
```

## <a name="module-evidently.calculations.stattests.fisher_exact_stattest"></a>fisher_exact_stattest module

Fisher’s exact test of two samples.

Name: “fisher_exact”

Import:

```python
>>> from evidently.calculations.stattests import fisher_exact_test
```

Properties:
- only for categorical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import fisher_exact_test
>>> options = DataDriftOptions(all_features_stattest=fisher_exact_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="fisher_exact")
```

## <a name="module-evidently.calculations.stattests.g_stattest"></a>g_stattest module

G-test of two samples.

Name: “g_test”

Import:

```python
>>> from evidently.calculations.stattests import g_test
```

Properties:
- only for categorical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import g_test
>>> options = DataDriftOptions(all_features_stattest=g_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="g_test")
```

## <a name="module-evidently.calculations.stattests.hellinger_distance"></a>hellinger_distance module

Hellinger distance of two samples.

Name: “hellinger”

Import:

```python
>>> from evidently.calculations.stattests import hellinger_stat_test
```

Properties:
- only for categorical and numerical features
- returns distance

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import hellinger_stat_test
>>> options = DataDriftOptions(all_features_stattest=hellinger_stat_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="hellinger")
```

## <a name="module-evidently.calculations.stattests.jensenshannon"></a>jensenshannon module

Jensen-Shannon distance of two samples.

Name: “jensenshannon”

Import:

```python
>>> from evidently.calculations.stattests import jensenshannon_stat_test
```

Properties:
- only for categorical and numerical features
- returns distance

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import jensenshannon_stat_test
>>> options = DataDriftOptions(all_features_stattest=jensenshannon_stat_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="jensenshannon")
```

## <a name="module-evidently.calculations.stattests.kl_div"></a>kl_div module

Kullback-Leibler divergence of two samples.

Name: “kl_div”

Import:

```python
>>> from evidently.calculations.stattests import kl_div_stat_test
```

Properties:
- only for categorical and numerical features
- returns divergence

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import kl_div_stat_test
>>> options = DataDriftOptions(all_features_stattest=kl_div_stat_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="kl_div")
```

## <a name="module-evidently.calculations.stattests.ks_stattest"></a>ks_stattest module

Kolmogorov-Smirnov test of two samples.

Name: “ks”

Import:

```python
>>> from evidently.calculations.stattests import ks_stat_test
```

Properties:
- only for numerical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import ks_stat_test
>>> options = DataDriftOptions(all_features_stattest=ks_stat_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="ks")
```

## <a name="module-evidently.calculations.stattests.mann_whitney_urank_stattest"></a>mann_whitney_urank_stattest module

Mann-Whitney U-rank test of two samples.

Name: “mannw”

Import:

```python
>>> from evidently.calculations.stattests import mann_whitney_u_stat_test
```

Properties:
- only for numerical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import mann_whitney_u_stat_test
>>> options = DataDriftOptions(all_features_stattest=mann_whitney_u_stat_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="mannw")
```

## <a name="module-evidently.calculations.stattests.psi"></a>psi module

PSI of two samples.

Name: “psi”

Import:

```python
>>> from evidently.calculations.stattests import psi_stat_test
```

Properties:
- only for categorical and numerical features
- returns PSI value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import psi_stat_test
>>> options = DataDriftOptions(all_features_stattest=psi_stat_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="psi")
```

## <a name="module-evidently.calculations.stattests.registry"></a>registry module


### class StatTest(name: str, display_name: str, func: Callable[[pandas.core.series.Series, pandas.core.series.Series, str, float], Tuple[float, bool]], allowed_feature_types: List[str], default_threshold: float = 0.05)
Bases: `object`

#### Attributes: 

##### &nbsp;&nbsp;&nbsp;&nbsp; allowed_feature_types : List[str] 

##### &nbsp;&nbsp;&nbsp;&nbsp; default_threshold : float  = 0.05 

##### &nbsp;&nbsp;&nbsp;&nbsp; display_name : str 

##### &nbsp;&nbsp;&nbsp;&nbsp; func : Callable[[Series, Series, str, float], Tuple[float, bool]] 

##### &nbsp;&nbsp;&nbsp;&nbsp; name : str 

### exception StatTestInvalidFeatureTypeError(stattest_name: str, feature_type: str)
Bases: `ValueError`


### exception StatTestNotFoundError(stattest_name: str)
Bases: `ValueError`


### class StatTestResult(drift_score: float, drifted: bool, actual_threshold: float)
Bases: `object`

#### Attributes: 

##### &nbsp;&nbsp;&nbsp;&nbsp; actual_threshold : float 

##### &nbsp;&nbsp;&nbsp;&nbsp; drift_score : float 

##### &nbsp;&nbsp;&nbsp;&nbsp; drifted : bool 

### get_stattest(reference_data: Series, current_data: Series, feature_type: str, stattest_func: Optional[Union[str, Callable[[Series, Series, str, float], Tuple[float, bool]], StatTest]])

### register_stattest(stat_test: StatTest)
## <a name="module-evidently.calculations.stattests.t_test"></a>t_test module

T test of two samples.

Name: “t_test”

Import:

```python
>>> from evidently.calculations.stattests import t_test
```

Properties:
- only for numerical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import t_test
>>> options = DataDriftOptions(all_features_stattest=t_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="t_test")
```

## <a name="module-evidently.calculations.stattests.tvd_stattest"></a>tvd_stattest module

Total variation distance of two samples.

Name: “TVD”

Import:

```python
>>> from evidently.calculations.stattests import tvd_test
```

Properties:
- only for numerical features
- returns distance

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import tvd_test
>>> options = DataDriftOptions(all_features_stattest=tvd_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="TVD")
```

## <a name="module-evidently.calculations.stattests.utils"></a>utils module


### generate_fisher2x2_contingency_table(reference_data: Series, current_data: Series)
Generate 2x2 contingency matrix for fisher exact test
:param reference_data: reference data
:param current_data: current data


* **Raises**

    `ValueError` – if reference_data and current_data are not of equal length



* **Returns**

    contingency_matrix for binary data



* **Return type**

    contingency_matrix



### get_binned_data(reference_data: Series, current_data: Series, feature_type: str, n: int, feel_zeroes: bool = True)
Split variable into n buckets based on reference quantiles
:param reference_data: reference data
:param current_data: current data
:param feature_type: feature type
:param n: number of quantiles


* **Returns**

    % of records in each bucket for reference
    current_percents: % of records in each bucket for current



* **Return type**

    reference_percents



### get_unique_not_nan_values_list_from_series(current_data: Series, reference_data: Series)
Get unique values from current and reference series, drop NaNs


### permutation_test(reference_data, current_data, observed, test_statistic_func, iterations=100)
Perform a two-sided permutation test
:param reference_data: reference data
:param current_data: current data
:param observed: observed value
:param test_statistic_func: the test statistic function
:param iterations: number of times to permute


* **Returns**

    two-sided p_value



* **Return type**

    p_value


## <a name="module-evidently.calculations.stattests.wasserstein_distance_norm"></a>wasserstein_distance_norm module

Wasserstein distance of two samples.

Name: “wasserstein”

Import:

```python
>>> from evidently.calculations.stattests import wasserstein_stat_test
```

Properties:
- only for numerical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import wasserstein_stat_test
>>> options = DataDriftOptions(all_features_stattest=wasserstein_stat_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="wasserstein")
```

## <a name="module-evidently.calculations.stattests.z_stattest"></a>z_stattest module

Mann-Whitney U-rank test of two samples.

Name: “mannw”

Import:

```python
>>> from evidently.calculations.stattests import mann_whitney_u_stat_test
```

Properties:
- only for numerical features
- returns p-value

### Example

Using by object:

```python
>>> from evidently.options import DataDriftOptions
>>> from evidently.calculations.stattests import mann_whitney_u_stat_test
>>> options = DataDriftOptions(all_features_stattest=mann_whitney_u_stat_test)
```

Using by name:

```python
>>> from evidently.options import DataDriftOptions
>>> options = DataDriftOptions(all_features_stattest="mannw")
```


### proportions_diff_z_stat_ind(ref: DataFrame, curr: DataFrame)

### proportions_diff_z_test(z_stat, alternative='two-sided')
