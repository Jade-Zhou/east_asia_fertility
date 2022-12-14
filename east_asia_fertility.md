An investigation into female literacy and fertility rate in Southeast
Asian countries
================
Jue Zhou
11/7/2019

## Introduction

Gary Becker, the famous economist and sociologist at the University of
Chicago, was renowed for his attribution to the study of human capital.
He argued that people’s decision on child bearing can be seen as
rational and utility maximizing, and thus constructed an economic model
for family’s child bearing decisions. His theory of fertility suggests
that women’s educational level influence fertility rate in two ways:
first is an incentive effect, that more educated women have higher
opportunity costs of bearing children in terms of lost income; second is
the change in household bargaining power, which assumes that more
educated women are better able to support themselves and have more
bargaining power, including on family size (Becker, 1960).

While follow-up research generally supports the effect of female
literacy on fertility decline, some recent studies report no significant
correlation between female education and fertility and attribute the
changes to other factors, such as the rise of income, urbanization, “son
preference”, access to public health services. (e.g., United Nations,
1993; Jeffery and Jeffery, 1996; Vlassoff, 1996)

In this report, I intend to conduct an exploratory analysis into the
relationship between fertility decline and female education using the
cases of several Southeast Asian countries: Indonesia, Malaysia,
Philippines, Thailand, and Viet Nam. They were named as *Tiger Cub
Economies* in 1990s for their similar export-driven economic policy. At
the same time of newly industrial transition in the 1990s, they also
experienced a population transition marked by the decrease in fertility
rate. Similar economic development model, cultural backgrounds and lack
of family planning programmes make these countries comparable.

## Data

Data I used in my analysis comes from **Wittgenstein Centre for
Demography and Global Human Capital** (Available at [this
link](http://www.wittgensteincentre.org/dataexplorer).) Wittgenstein
centre provides a set of different scenarios of future population and
human capital trends in 201 countries of the world to 2100. The result
and update of the population projections by levels of educational
attainment are based on the work of a large team of researchers at the
Wittgenstein Centre for Demography and Global Human Capital and at other
institutions. New version of the datasets also includes the
reconstruction of population by levels of educational attainment from
1950 to 2015 for 185 countries.

## The General Change of Fertility Rate

Total fertility rate (TFR) in simple terms refers to total number of
children born or likely to be born to a woman in her life time if she
were subject to the prevailing rate of age-specific fertility in the
population (WHO). The following graph shows the general change of
fertility rate in the five countries listed above. All of them have
experienced a dramatic decrease in fertility rate over the past half
century, from over 6 to around 2. Three of them, Thailand, Viet Nam, and
Malaysia, have reached the replacement level of fertility (2.1 children
per woman). Although the fertitlity rate of the other four countries
have kept stable in recent years, the fertility rate of Philippines is
still in a decreasing
trend.

<img src="east_asia_fertility_files/figure-gfm/fertility-1.png" width="768" />

## Findings

### Fertility rate and the average schooling years of women of childbearing age

<img src="east_asia_fertility_files/figure-gfm/schoolyears-1.png" width="768" />

To determine the relationship between female literacy and fertility
rate, here I used the average schooling years of women in childbearing
age to measure the level of female literacy. Similar to previous study,
the result shows there is a negetive correlation between women’s
education years and total fertility
rate.

### Fertility rate and percent of women receiving relatively higher education

Although the graph above shows the relationship between female education
and fertility, there appears to be some lack of clarity as to the
pathways through which it operates. Here I hope to distingish between
(i) the incentive effect—-the opportunity costs of bearing children, and
(ii) the change in household bargaining power. For the incentive effect,
I examined the relationship between percent of women in childbearing age
who have received at least upper secondary education and total fertility
rate. If higher education generally means higher income and higher
opportunity costs of bearing children, would there be a negative
relationship between these two
variables?

<img src="east_asia_fertility_files/figure-gfm/higheredu-1.png" width="768" />

Within single country level, the answer seems to be yes. The higher
percent of women whose educational level is at least upper secondary,
the lower total fertility rate goes. However, if we compare the
relationship across countries, Philippines appears to be a very
different case. Although the percent of women receiving higher level
education exceeds all the other countries, its fertility rate is rather
high.

### Fertility rate and educational gap between males and females

Household bargaining power model claims women’s education not only
increases the opportunity cost of childbearing, it also strengthens
their bargaining power on the family size. When considering the power
structure in a family, the male partner’s socio-economic status should
also be taken into consideration. Here I use the educational gap between
male and female to measure the bargaining power
change.

<img src="east_asia_fertility_files/figure-gfm/edugap-1.png" width="768" />

Similar to what we find above, we can see a positive correlation between
the education gap and total fertility rate, which means as the closing
of educational gap is correlated with the decline in total fertility
rate. However, the case of Philipines is still very different from the
other four countries. Its total fertility rate remains relatively high
although its education gap has gone to negative in recent years.

Although here we do not have further data to dig into this phenomena,
the fact that Philippines is not only a commodity-export country but
also a large labor-export country might helps to explain it. According
to a source in 2015, the Philippine government issued employment
contracts to at least 1.8 million temporary migrant workers, the
majority of them are women (Mendoza, 2015). If the female in the family
is aborad working as migrant workers, and the male takes on most part of
the job of child rearing, the opportunity cost and household bargaining
power no longer serves as efficient mechanisms for decline in fertility
rate.

### Fertility rate and Sex Ratio

Besides the factor of female literacy, some scholars also argue for the
possible role of ‘son preference’ in influencing fertility. This concern
arises from the common-sense observation that desire for a specified
number of sons often interferes with the transition towards small-family
norms.

Here I used the sex ratio of the population aged 0-4 to measure the
gender preference in
childbearing.

<img src="east_asia_fertility_files/figure-gfm/sexratio-1.png" width="768" />

The graph shows that except for Thailand, the higher sex ratio of 0-4
age range is (which might reflects a son preference), the higher total
fertility rate is, which indicates son preference might also plays a
role in enhancing fertility rate.

## Conclusion

Analysis above indicates that increase in women’s educational level does
have a negative influence on total fertility rate of a country. However,
comparison across countries shows that female literacy is not the only
mechanism. Instead, economic mode, division of labor and gender
preference might also play a part in dermining the fertility rate.
Obviously, simple correlation analysis is not enough to shed light on
the causal relationships and mechanisms behind the population
transition. I hope to further investigate into this problem by applying
multivariate regression and other statistical methods in the following
weeks.

## Bibliography

Becker, Gary S. 1960. “An Economic Analysis of Fertility.” In National
Bureau Committee for Economic Research, Demographic and Economic Change
in Developed Countries, a Conference of the Universities. Princeton,
N.J.: Princeton University Press

Jeffery, R and P Jeffery. 1997. “Population, Gender and Politics:
Demographic Change in Rural North India.” Cambridge: Cambridge
University Press.

Mendoza, D. R. 2015. “Human capital: The Philippines’ labor export
model”. World Politics Review.

United Nations. 1993, Women’s Education and Fertility Behavior: A Case
Study of Rural Maharashtra. New York: Department of Economic and Social
Information and Policy Analysis, United Nations.

Vlassoff, Carol. 1996. “Against the Odds: The Changing Impact of
Schooling on Female Autonomy and Fertility in an Indian Village”. In
Jeffery, R and A Basu. 1996. Girls’ Schooling, Women’s Autonomy, and
Fertility Change in South Asia. New Delhi: Sage.
