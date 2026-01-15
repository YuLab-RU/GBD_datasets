# WHO TB Burden Data: Incidence, Mortality, and Population

Tuberculosis remains one of the world’s deadliest infectious diseases. WHO estimates that 10.6 million people fell ill with TB in 2021, and 1.6 million died from the disease. Monitoring TB burden is essential to guide national responses and global strategies.

This dataset contains global tuberculosis (TB) burden estimates from the World Health Organization. The dataset includes country-level indicators such as TB incidence, mortality, case detection rates, and population estimates across multiple years. These metrics help researchers, public health professionals, and learners understand the scale and distribution of TB worldwide.


## Data Dictionary

| variable | class | description |
|:---|:---|:---|
| country | character | Country or territory name |
| g_whoregion | character | WHO region |
| iso_numeric | integer | ISO numeric country/territory code |
| iso2 | character | ISO 2-character country/territory code. Note that Namibia's code ("'NA'") includes single quotes to avoid being encoded as missing |
| iso3 | character | ISO 3-character country/territory code |
| year | integer | Year of observation |
| c_cdr | double | Case detection rate (all forms) [also known as TB treatment coverage], percent |
| c_newinc_100k | double | Case notification rate, which is the total of new and relapse cases and cases with unknown previous TB treatment history per 100 000 population (calculated) |
| cfr | double | Estimated TB case fatality ratio |
| e_inc_100k | double | Estimated incidence (all forms) per 100 000 population |
| e_inc_num | integer | Estimated number of incident cases (all forms) |
| e_mort_100k | double | Estimated mortality of TB cases (all forms) per 100 000 population |
| e_mort_exc_tbhiv_100k | double | Estimated mortality of TB cases (all forms, excluding HIV) per 100 000 population |
| e_mort_exc_tbhiv_num | integer | Estimated number of deaths from TB (all forms, excluding HIV) |
| e_mort_num | integer | Estimated number of deaths from TB (all forms) |
| e_mort_tbhiv_100k | double | Estimated mortality of TB cases who are HIV-positive, per 100 000 population |
| e_mort_tbhiv_num | integer | Estimated number of deaths from TB in people who are HIV-positive |
| e_pop_num | integer | Estimated total population number |

## Acknowledgement

Data source: [the getTBinR R package by Sam Abbott](https://samabbott.co.uk/getTBinR/). Thank you to [Darakhshan Nehal](https://github.com/darakhshannehal) for curating. 

