Data-driven evaluation of minor real-estate investments
=======================================================

***IBM Data Science Professional Certificate, 10th month - Capstone Project***

**Author:** *Balazs Pukli*

# Introduction
Evaluation tasks of real-estate may introduce difficulty into an investors workflow. Major real-estate developers can afford to tackle this problem by adding purchases of expertise to their budget, but at smaller scales, the margins do not enable such expenses within the boundaries of healthy profitability.

Cheap, software-based solutions present a possible way to solve this problem, and presumably there is a market for them, since small-scale investors exist. As an alternative market, I see mortgage creditor banks using a similar software for quick pre-evaluation of collateral items, so that they can provide preliminary offers to customers.

The project aims to discover some of the possible sources of data, and use-cases thereof, which can be used during the development of such a solution.

## The problem: how to evaluate real-estate investment opportunities at small scale?
This problem brings a variety of complexities which make resolution hard, e.g.:
 - **economy in the area**
 - **historical prices**
 - supply & demand
    - new construction
    - secondary market
 - parameters of the given piece of real-estate
 - credit economy
 - government incentives

### Scope
**Focus will be on the first two points, seen as bold text.** I also limit the scope of the project to the Hungarian market for now.

## The data: local economy characteristics and historical real-estate prices
Addressing these two areas of the problem, I'm using the **Foursquare API** and some **statistics provided by the Hungarian government**, as I'm building a prototype based on data in Hungary.

### Using the Foursquare API
I will use the Foursquare API to gain insight into how well diversified the economy is in the area, by using the *explore venues by location* feature. Such insight can help to estimate the value of nearby real-estate in many ways, for example, these factors can translate into a higher value:
 - if there are more things to do in the area in terms of recreation
 - if there are sufficient available sources to buy household items, or even go to restaurants, coffee shops, or use other services
 - if there are more jobs available

### Using the government stats
The real-estate market data provides average prices only, without any knowledge on any of the parameters of the real-estate. That is a large limitation, but on the other hand, there are average prices for each smaller location within the country, and there are multiple instances of this database, corresponding to each year in the last decade. That means that possibly useful estimations can be made based on this data, based on the differences of localities and also trends forming through time.