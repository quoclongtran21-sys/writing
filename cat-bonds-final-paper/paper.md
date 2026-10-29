---
title: "Are Catastrophe Bonds Really Zero-Beta Assets? Diversification Benefits in Normal Markets and Financial Crises"
author: "Tran Nguyen Quoc-Long"
---

# 1. Introduction

A catastrophe (CAT) bond lets an insurer, a reinsurer or a government pass part of its exposure to a natural disaster to capital-market investors. The sponsor pays a premium, the investors put up principal that is held as collateral, and if a specified hurricane, earthquake or other event occurs before maturity, part or all of that principal goes to the sponsor (Cummins, 2008). Froot (2001) showed that catastrophe reinsurance in the 1990s was priced far above expected losses and traced the gap to frictions in the supply of reinsurance capital. Securitization was one answer: it opens catastrophe risk to investors whose combined wealth is much larger than the capital of the reinsurance industry.

To attract those investors, the market offered a simple argument. Whether a hurricane hits Florida or an earthquake hits Tokyo does not depend on the stock market, so the losses on a CAT bond should be unrelated to the losses on stocks and corporate bonds. In CAPM terms, CAT bonds would be zero-beta assets. Their spread over the risk-free rate should then do little more than cover expected losses, and any spread well above that level would be an attractive reward for a risk that adds nothing to the systematic risk of a diversified portfolio.

The argument concerns the natural event, while the investor holds a financial security. A CAT bond is a contract with a special purpose vehicle, its principal sits in a collateral account, its price comes from dealer quotes, and it is held by funds that may need cash at the same moment as everyone else. Each of these features can carry financial stress into the bond when no catastrophe has happened. Whether they do so is an empirical question, and the published answers contradict each other.

Three positions can be distinguished. The first supports the zero-beta view: Carayannopoulos and Perez (2015) find that CAT bonds behaved as zero-beta assets outside crisis periods, and Haffar and Le Fur (2022) find that, of the assets they study, CAT bonds add the least to the probability of extreme joint movements with an equity portfolio. The second rejects it: Gürtler, Hibbeln and Winkelvos (2016) conclude from the link between CAT bond premiums and corporate bond spreads that CAT bonds should not be regarded as zero-beta securities, and Carayannopoulos and Perez themselves find that CAT bond returns became correlated with the market after the collapse of Lehman Brothers. The third makes the answer depend on the period: Drobetz, Schröder and Tegtmeier (2020) find that CAT bonds are a diversifier but a poor hedge, and a strong safe haven against extreme stock market declines only after the financial crisis, while Feng and Zeng (2025) find a safe haven against stocks after the COVID-19 outbreak.

The difference matters for an investor. A diversifier lowers the variance of a portfolio on average. A safe haven holds up when the rest of the portfolio is in a crash. An investor who buys CAT bonds for the second property when they only have the first is exposed at the worst moment.

My research question is: **to what extent do CAT bonds retain their diversification benefits during financial stress, and why do published studies reach different answers?** I argue that the disagreement has little to do with whether catastrophes occur and much to do with how catastrophe risk is collateralised, priced and measured. It comes from four sources: the property being tested (diversifier, hedge or safe haven), the collateral structure in force during the sample, the type of stress (a shortage of funding or a fall in equity prices), and the way CAT bond returns are measured. As my personal contribution, I propose a decomposition of the CAT bond return into an insurance core, whose losses are independent of markets for natural perils, and a financial wrapper, whose market exposure changes with the bond's structure and with the stress episode. The decomposition sorts the episodes studied in the literature into four regimes, makes predictions that can be tested, and leads to proposals for investors.

Section 2 explains how CAT bonds work, defines the three properties that the literature tests, presents the three articles in detail and adds the studies that diverge from them. Section 3 contains my analysis: the decomposition, the four regimes, the measurement problems and the proposed solutions. Section 4 concludes.

# 2. Literature review

## 2.1 How a CAT bond works, and where financial risk can enter

A sponsor sets up a special purpose vehicle (SPV) that sells notes to investors and signs a reinsurance contract with the sponsor. The proceeds of the notes are placed in a collateral trust account. Investors receive the return earned by the collateral plus a fixed risk spread paid out of the sponsor's premium. If a qualifying event occurs, the collateral is released to the sponsor to pay its claims and investors lose part or all of their principal (Cummins, 2008). The trigger can be the sponsor's own losses (indemnity), an industry loss index, a modelled loss, or a physical parameter such as wind speed. Index and parametric triggers reduce moral hazard at the cost of basis risk for the sponsor (Cummins, 2008; Cummins and Weiss, 2009).

Several parts of this structure have nothing to do with nature. One is the **collateral**. Before 2009, many deals did not simply hold government securities. The collateral was invested in other assets, and an investment bank promised the SPV a money-market return through a total return swap, making up any shortfall in the value of the collateral. Lehman Brothers Special Financing was the swap counterparty for four CAT bonds: Ajax Re, Carillon, Newton Re and Willow Re. When Lehman failed in September 2008, the collateral lost its guarantee. Ajax Re paid all its interest but could not repay its principal in full at maturity in May 2009 because the collateral assets were worth less than the notes (Artemis, 2009). Carayannopoulos and Perez (2015) attribute the crisis effect on CAT bonds mainly to weaknesses in the composition and structure of the trust account, and they observe that new bonds issued from 2009 onward used improved structures. No new CAT bond used a total return swap after 2009, and by the end of 2011 Treasury money-market funds accounted for more than 60 percent of collateral structures, alongside structured notes and tri-party repurchase agreements (Artemis, 2011).

Another is **liquidity**. CAT bonds trade over the counter and not very often. Using 9,393 secondary-market trades reported to TRACE between 2015 and 2019, Herrmann and Hibbeln (2023) find that liquidity is lower for riskier bonds and for bonds far from maturity, and they estimate that the liquidity premium accounts for about a fifth of the observed CAT bond yield spread. A premium of that size can move when dealers and investors run short of capital, which is also when stock prices fall (Brunnermeier and Pedersen, 2009).

Measurement is a further source of financial noise. Most empirical studies use Swiss Re's CAT bond indices. Drobetz et al. (2020) describe the index they use as tracking secondary-market bid indications that Swiss Re provides to investors each week. An index built from dealer quotes tends to be smoothed: it absorbs news with a delay, which lowers its measured volatility and its contemporaneous correlation with other markets (Getmansky, Lo and Makarov, 2004).

## 2.2 Diversifier, hedge and safe haven: what each test measures

The articles reviewed here use, explicitly or not, the definitions of Baur and Lucey (2010). A **hedge** is an asset that is uncorrelated or negatively correlated with another asset or portfolio on average. A **diversifier** is positively, but not perfectly, correlated with it on average. A **safe haven** is uncorrelated or negatively correlated with it during extreme market declines. Baur and McDermott (2010) distinguish strong and weak versions: a strong hedge or safe haven is negatively correlated with the market, a weak one is uncorrelated. In this terminology, an asset whose beta is zero on average is a weak hedge, which is a stronger property than being a diversifier.

These properties are distinct: an asset can be a good diversifier and still fail as a safe haven. The zero-beta claim, which says the beta is zero at all times, amounts to "weak hedge plus weak safe haven", so evidence of diversification does not confirm it. The definitions are also about correlation, not about price. A statistical safe haven can lose money in a crash as long as its losses do not move with the market's. An investor who has to sell during a crisis cares about the price received, so the economic meaning of a safe haven is stricter than the statistical one.

The word "strong" also changes meaning between studies. In the two-stage framework used by Drobetz et al. (2020), taken from Bouri et al. (2017), the safe-haven verdict rests on the coefficients of extreme-week dummies, which measure how the correlation changes in those weeks. A strong safe haven in that sense is a significant fall in the correlation, which does not require the correlation to become negative as Baur and McDermott's definition does. In this paper, "strong" refers to the regression sense when I discuss Drobetz et al. and to a negative correlation otherwise.

The tools differ as well. A beta is the covariance with the market divided by the market's variance, and a correlation scales the same covariance by both volatilities. A copula separates the dependence between two series from their individual distributions and can measure tail dependence, the probability of an extreme loss in one series given an extreme loss in the other. These tools can give different verdicts on the same data, and Forbes and Rigobon (2002) showed one reason: when two assets share a common factor, a rise in market volatility raises their measured correlation even if the underlying relation has not changed, so correlations estimated in crisis windows are biased upward unless they are corrected.

## 2.3 Carayannopoulos and Perez (2015): zero beta, except in a crisis

The first article asks two questions: are CAT bonds zero-beta investments, and do they diversify a portfolio? Over January 2002 to October 2013, the authors study the joint dynamics of CAT bond returns and the returns of the stock, corporate bond and government bond markets with a multivariate GARCH model. From the estimated conditional covariances they compute dynamic hedge ratios, the conditional covariance with each market divided by that market's conditional variance. Because a hedge ratio defined this way is a beta, they read the series as time-varying betas.

The results depend on the period. Outside the crisis, the betas are indistinguishable from zero and CAT bonds look like the zero-beta asset of the textbook argument. With the collapse of Lehman Brothers, CAT bond returns became significantly correlated with the market. The size of the effect is small: the hedge ratios of CAT bonds stay very close to zero in all sub-periods, while those of government bonds change markedly after September 2008. The authors conclude that the crisis affected CAT bonds much less than the other asset classes, so CAT bonds still diversified a portfolio, and that CAT bond betas returned to their pre-crisis levels once bonds with improved structures were issued from 2009 onward, which they read as the market's approval of those structures.

The strength of the article is that it treats beta as a variable. The time-varying hedge ratios show when the zero-beta property broke down, and the timing points to the trust-account structure that the authors identify as the main weakness. Its limit, for my question, is that a beta estimated on returns cannot say which part of the bond moved with the market. A fall in the value of Lehman-guaranteed collateral, a rise in the premium demanded by investors who needed cash, and a stale price catching up after a quiet period would all appear as a positive beta. The article also studies a single crisis, and an unusual one for CAT bonds, since a swap counterparty failed during it. Timing adds a further difficulty. Hurricane Ike made landfall in Texas on 13 September 2008, two days before Lehman Brothers filed for bankruptcy, so in weekly data a catastrophe event and a financial shock can fall in the same observation. In a short crisis window such a coincidence carries a large weight, and a crisis beta is only interpretable once the two are separated.

## 2.4 Drobetz, Schröder and Tegtmeier (2020): a diversifier, and a safe haven only after the crisis

The second article widens the comparison to an international multi-asset portfolio. The authors pair the Swiss Re Global Unhedged CAT Bond Performance Index with six asset classes: global stocks, bonds, real estate, commodities, private equity and infrastructure, using weekly returns from 2002 to 2018. Their method has two stages, following Bouri et al. (2017). First, they estimate dynamic conditional correlations (DCC) between the CAT bond index and each asset class. Second, they regress these correlations on dummy variables that mark the weeks in which the other asset's return falls in its extreme lower tail. The constant of the regression measures the average correlation, which settles the hedge-or-diversifier question. The coefficients on the dummies measure how the correlation changes in extreme weeks, which settles the safe-haven question.

According to the article, CAT bonds are a poor hedge, since their average correlation with the other asset classes is positive. They are an effective diversifier against all six classes. They are a strong safe haven against extreme declines of the stock market, but only during the post-crisis period. In the earlier sub-periods this property is absent.

This article is the closest to my question because it separates the three properties and tests them by sub-period. It also contradicts the first article on average behaviour: a positive average correlation is incompatible with the zero beta that Carayannopoulos and Perez find outside crises. And it sharpens the puzzle. If the zero-beta argument were complete, the safe-haven property would hold in every period, because the probability of a hurricane does not depend on the state of financial markets. Two features of the design matter for the interpretation. The index is built from bid indications, not trades, so weekly correlations may understate co-movement when quotes adjust slowly. And the extreme-week dummies identify stress through the other asset's return only. A week in which stock prices fall while funding markets work normally and a week of forced selling in a funding crisis are treated as the same event.

## 2.5 Haffar and Le Fur (2022): little extreme co-movement

The third article studies the dependence structure itself. The authors model each return series with a GARCH process and join the series with copulas, which lets the dependence change over time and differ between ordinary and extreme outcomes. Their portfolio combines CAT bonds with six stock markets: the CAC 40, the Dow Jones Industrial Average, the EURO STOXX 50, the FTSE 100, the Hang Seng and the Nikkei 225. The authors present the paper as the first to analyse the dependence structure and diversification value of CAT bonds with copulas.

Their findings are the most favourable of the three. CAT bonds display the highest risk-adjusted performance among the assets studied, they are one of the best diversifiers, and they are the asset that raises the probability of extreme co-movements with the benchmark portfolio the least.

The copula approach answers a question that correlation-based studies cannot answer directly: do the two assets crash together? On that question, the article supports the zero-beta view. The result has limits. The alternatives against which CAT bonds are ranked are stock indices, which depend strongly on each other and on an equity benchmark by construction, so ranking first among them on extreme co-movement is a modest test. The headline results describe the dependence structure as a whole. They do not tell an investor whether the probability of a joint extreme rises in a funding crisis like that of 2008. And if the CAT bond series is an index of quoted prices, as in most of this literature, its volatility is understated and its risk-adjusted performance overstated (Getmansky et al., 2004).

## 2.6 Other studies: divergent and supporting evidence

Two studies of CAT bond prices take the opposite side. Gürtler et al. (2016) analyse premiums in the secondary market and find that both the financial crisis and Hurricane Katrina had a significant effect on them. They also find a positive relation between corporate bond spreads and CAT bond premiums, a dependence that grew stronger during the crisis, and conclude that CAT bonds should not be regarded as zero-beta securities. Braun (2016), who models spreads at issuance, finds that apart from the expected loss, the covered territory, the sponsor and the reinsurance cycle, the spreads of comparably rated corporate bonds help explain CAT bond spreads. These two studies concern the price of risk and say nothing directly about realized losses. They show that the premium investors demand for catastrophe risk moves with the premium they demand for credit risk, outside crises as well as during them.

A recent study supports the favourable view for a later crisis. Feng and Zeng (2025) apply a DCC-GARCH model to an international multi-asset portfolio before and during the COVID-19 pandemic. They find that CAT bonds were a diversifier over the whole sample and a safe haven against stocks and private equity after the outbreak. The results hold with desmoothed returns, which addresses the quote-smoothing problem described above, but the authors also find that hedge ratios are sensitive to extreme weather events.

The same period produced a case in which the zero-beta argument fails by design. The World Bank's 2017 pandemic bonds put 16.67 percent of the principal of the Class A notes and all of the principal of the Class B notes at risk if a qualifying pandemic occurred (Government Actuary's Department, 2021), and COVID-19 met the trigger conditions during the same shock that hit equity markets.

Table 1 compares the three main articles.

**Table 1. The three articles compared**

| | Carayannopoulos and Perez (2015) | Drobetz, Schröder and Tegtmeier (2020) | Haffar and Le Fur (2022) |
|:--|:--|:--|:--|
| Question | Are CAT bonds zero-beta, and did the subprime crisis change this? | Are CAT bonds a diversifier, a hedge or a safe haven? | How do CAT bonds depend on equity markets, including in the tails? |
| Data | CAT bonds vs stocks, corporate bonds, government bonds; Jan. 2002 to Oct. 2013 | Swiss Re index vs global stocks, bonds, real estate, commodities, private equity, infrastructure; weekly, 2002 to 2018 | CAT bonds and six stock indices (CAC 40, DJIA, EURO STOXX 50, FTSE 100, Hang Seng, Nikkei 225) |
| Method and statistic | Multivariate GARCH; dynamic hedge ratios read as betas | DCC, then regression of the DCC on extreme-week dummies | Copula-GARCH; time-varying and tail dependence |
| What counts as stress | The crisis period after Lehman's failure | Weeks of extreme decline in the other asset, by sub-period | Joint extreme outcomes in the tails |
| Main conclusion | Zero-beta only outside crises; small crisis effect; betas back to pre-crisis levels after the 2009 structures | Poor hedge; effective diversifier; strong safe haven against stocks only post-crisis | Highest risk-adjusted performance; one of the best diversifiers; least increase in extreme co-movement |
| Position on the zero-beta claim | Holds in normal times (weak hedge), fails after Lehman | Rejected on average (positive correlation), partly restored in post-crisis stress | Supported for extreme co-movement with equities |

# 3. Analysis

## 3.1 What the articles actually disagree about

The contradictions are of two kinds. The first concerns average behaviour. Outside crises, Carayannopoulos and Perez cannot distinguish the beta of CAT bonds from zero, which makes CAT bonds a weak hedge in Baur and Lucey's terms. Drobetz et al. find a positive average correlation, which makes them a diversifier but a poor hedge. Gürtler et al. and Braun find that CAT bond premiums move with corporate spreads even outside crises. The second and sharper contradiction concerns stress. Carayannopoulos and Perez and Gürtler et al. find that CAT bonds moved with markets in the 2007-2009 crisis. Drobetz et al. find a strong safe haven against stocks only after that crisis, Feng and Zeng find a safe haven after the COVID-19 outbreak, and Haffar and Le Fur find the weakest extreme co-movement with equities of all the assets they study. On one point all the studies agree: CAT bonds lower portfolio risk on average, whether they are classed as a weak hedge or as a diversifier.

The negative findings on stress come from 2007-2009 and the positive ones from later periods. Three explanations are available: the bonds changed, the crises differed, or the methods differed. A simpler account would say that 2008 was a special case and the rest is a matter of method. My argument is that all three explanations hold together, that a decomposition can separate them, and that it makes a prediction the simpler account does not make (Section 3.5).

## 3.2 A decomposition of the CAT bond return

I write the return of a CAT bond, or of an index of CAT bonds, over one period as

::: {custom-style="Equation"}
*R*~t~ = *r*~t~ + *s* − *ℓ*~t~ − *D*·Δ*π*~t~ − *k*~t~	(1)
:::

where *r*~t~ is the return on the collateral, *s* is the contractual spread accrued over the period, *ℓ*~t~ is the loss caused by catastrophes (a realized loss, or a revaluation of the expected loss after an event), Δ*π*~t~ is the change in the premium investors require above the expected loss, *D* is the bond's spread duration, and *k*~t~ is the loss in collateral value caused by the failure of a counterparty or a fall in the value of the collateral assets. Defining *π* net of the expected loss keeps a revision of the expected loss in *ℓ*~t~ only.

The beta of the bond with respect to the market return *R*~m~ is the sum of the betas of its components, *β*~x~ = Cov(*x*~t~, *R*~m,t~)/Var(*R*~m,t~):

::: {custom-style="Equation"}
*β* = *β*~r~ − *β*~ℓ~ − *D*·*β*~π~ − *β*~k~	(2)
:::

The zero-beta argument is an assumption about *ℓ*~t~ only: natural catastrophes do not depend on financial markets, so *β*~ℓ~ = 0. The collateral earns a short-term money-market rate whose weekly variation is negligible, so *β*~r~ ≈ 0, and *s* is fixed by contract. What is left is

::: {custom-style="Equation"}
*β* ≈ −*D*·*β*~π~ − *β*~k~	(3)
:::

Under this assumption, the measured beta of a natural-catastrophe bond is the beta of its financial wrapper. I call the first term the **premium channel** and the second the **collateral channel**. When markets fall, the required premium rises (*β*~π~ < 0) and collateral losses, if possible at all, become more likely (*β*~k~ < 0), so both channels push the beta above zero in a crisis. The split follows the distinction of Campbell and Vuolteenaho (2004) between cash-flow beta and discount-rate beta: *ℓ*~t~ and *k*~t~ are cash-flow news, Δ*π*~t~ is discount-rate news. That distinction matters for investors. A price fall caused by a higher premium is recovered as the bond approaches maturity if no catastrophe occurs, so it is a loss mainly for a holder who has to sell.

Two qualifications apply. A very large catastrophe can move a regional stock market, as the Tōhoku earthquake of March 2011 moved Japanese equities, so against a regional benchmark *β*~ℓ~ is small rather than exactly zero. And the premium channel is not free of catastrophe risk in every sense, since *π* is the price investors charge for bearing it. What the decomposition separates is the occurrence of catastrophes, which markets do not drive, from the price and the packaging of catastrophe risk, which they can.

Equation (3) leads to the following predictions.

1. In calm markets the collateral channel is closed and the premium moves little, so *β* is small. It need not be exactly zero: the link between CAT premiums and corporate spreads found by Gürtler et al. (2016) and Braun (2016) exists outside crises, which is consistent with the positive average correlation found by Drobetz et al. (2020).
2. The collateral channel is open only when the collateral is exposed to the credit of a financial institution. It was open before 2009 and is close to closed for deals whose collateral is held in Treasury money-market funds.
3. The premium channel opens when holders of CAT bonds need cash at the moment the market falls. They sell, and dealers short of capital absorb the bonds only at a higher premium. When funding is scarce, market liquidity and funding liquidity reinforce each other (Brunnermeier and Pedersen, 2009), and when capital moves slowly into a market after such a shock, prices fall further than fundamentals justify and then recover gradually (Duffie, 2010). Herrmann and Hibbeln's (2023) estimate that liquidity accounts for about a fifth of CAT bond spreads shows that this channel has room to move prices. The same channel covers the evidence of Gürtler et al. and Braun: if the capital available to bear catastrophe risk shrinks with financial wealth, the price of catastrophe risk rises when credit spreads rise, as Froot's (2001) account of capital-driven catastrophe pricing would predict.

The decomposition also identifies the case in which the zero-beta claim fails at its root. If the peril is itself a macroeconomic shock, *β*~ℓ~ ≠ 0. For diversification purposes, pandemic bonds, and in my view bonds covering systemic cyber risk, belong to a different asset class from natural-catastrophe bonds.

## 3.3 Four stress regimes

Equation (3) suggests classifying stress episodes on two dimensions: whether the collateral was exposed to bank credit, and whether the episode was a funding crisis, in which investors needed cash, or a fall in equity prices while funding markets kept working. Table 2 places the evidence in this grid.

**Table 2. Stress regimes implied by the decomposition, with the evidence for each**

| | Funding crisis (investors need cash) | Equity sell-off, funding markets working |
|:--|:--|:--|
| **Collateral exposed to bank credit (pre-2009 swap structures)** | Both channels open: beta turns positive. *Evidence:* the crisis after Lehman's failure (Carayannopoulos and Perez, 2015; Gürtler et al., 2016); the four Lehman-backed bonds. | Only the insurance core is tested: beta close to zero. *Indirect evidence:* zero betas in non-crisis periods (Carayannopoulos and Perez, 2015). |
| **Collateral in Treasury money-market funds (post-2009)** | Premium channel only: a small fall, later reversed; at most a weak safe haven. *Evidence:* safe haven against stocks after the COVID-19 outbreak, with desmoothed returns (Feng and Zeng, 2025); March 2020 market reports. | Neither channel open: beta close to zero, at least a weak safe haven. *Evidence:* strong post-crisis safe haven against stocks (Drobetz et al., 2020), whose strong form the grid does not explain. |

Each of the main results can be placed in one cell. Since the grid was built after reading the evidence, this fit is not a test; it shows that the results are compatible, and Section 3.5 states how the grid could be proved wrong.

The top-left cell contains one episode, the months after Lehman's failure, when both channels were open. The crisis betas of Carayannopoulos and Perez and the link between CAT premiums and corporate spreads found by Gürtler et al. are what equation (3) predicts there. Carayannopoulos and Perez attribute much of the crisis effect to the collateral design that the market has since abandoned, but none of the reviewed evidence splits the crisis beta between the two channels.

The post-crisis safe haven of Drobetz et al. belongs to the bottom-right cell. After 2009 the collateral channel was closed, and in my reading the stock market declines of their post-crisis sample did not bring forced selling on the scale of late 2008, so the premium channel stayed weak and CAT bonds should be at least a weak safe haven. The grid does not predict the strong form that Drobetz et al. report, a significant fall in the correlation during extreme weeks. Equation (3) produces it only if the required premium falls when stocks fall, for instance through inflows into CAT bonds during an equity sell-off, which the reviewed evidence does not document. Index smoothing cannot explain it either, since the same index is used in every sub-period. This part of their result is left open. In their crisis sub-period both channels were open, so the absence of a safe haven there is what the grid predicts.

March 2020 is the main test of the bottom-left cell: collateral in Treasury funds combined with a severe scramble for cash. The framework predicts a fall driven by forced sales, no loss on collateral, and a recovery once capital returns. The best evidence is Feng and Zeng's, because it holds with desmoothed returns: CAT bonds remained a safe haven against stocks after the outbreak. Market reports agree. The Swiss Re price return index fell by 0.81 percent in the week to 20 March, with markdowns linked to bulk lists of bonds put up for sale (Insurance Insider ILS, 2020), and by May the sell-off was described as temporary (The Insurer, 2020). Because that index is built from quotes, the true fall was probably larger. The decomposition can still give it an order of magnitude: with a spread duration of one to two years, as for bonds with a few years to maturity, a 0.81 percent price fall corresponds to a rise of roughly 40 to 80 basis points in the required premium, which is of the same order as the average liquidity premium estimated by Herrmann and Hibbeln (2023). A bond can thus qualify as a statistical safe haven and still post a negative return in the week an investor needed to sell it.

The post-2009 period contains other candidates for this cell that the reviewed studies do not isolate: the strains on euro-area bank funding in 2011-2012, and September-October 2022, when stress in UK pension funds' liability-driven investment strategies coincided with Hurricane Ian's landfall in Florida on 28 September, a repeat of the Ike-Lehman coincidence.

Haffar and Le Fur's result reads, in this grid, as an average over the cells, dominated by calm weeks. The grid predicts stronger tail dependence in funding-crisis weeks alone.

## 3.4 Measurement choices that move the answer

Part of the divergence between the articles is statistical, and two biases pull in opposite directions.

The first is **smoothing**. If the index comes from bid indications that adjust with a lag, the observed return is a weighted average of current and past true returns, *R*^o^~t~ = *θ*~0~*R*~t~ + *θ*~1~*R*~t−1~ + … with weights summing to one (Getmansky et al., 2004). If the true returns are serially uncorrelated, the contemporaneous beta is *θ*~0~ times the true beta, and the correlation is scaled by *θ*~0~/√(Σ*θ*~j~²), a smaller reduction because smoothing also lowers the measured volatility. Both are biased toward zero. The bias is probably largest in a crisis, when quotes are updated less often. It makes CAT bonds look more like a safe haven than they are. Dimson (1979) betas, which add lagged market returns to the regression, recover the covariance that a stale price misses.

The second is **conditioning on volatility**. Suppose the CAT bond return is *β* times the market return plus an independent shock with volatility *σ*~ε~. The correlation is then *ρ* = *β*·*σ*~m~/√(*β*²*σ*~m~² + *σ*~ε~²), which rises with the market's volatility *σ*~m~ whenever *β* > 0 (Forbes and Rigobon, 2002). A correlation measured in a crisis window or in extreme weeks therefore overstates any co-movement that exists. If the true beta is zero, the bias disappears: conditioning on volatility can exaggerate co-movement, but it cannot create it.

Which bias matters depends on the method. A beta, as in Carayannopoulos and Perez, is free of the second bias but exposed to the first. A DCC regression on extreme weeks, as in Drobetz et al., is exposed to both. A copula on GARCH-filtered returns, as in Haffar and Le Fur, is not protected from the second bias by the filtering, because dividing each series by its own volatility leaves their correlation unchanged; its contribution is to measure dependence in the tails, and it still works on observed, possibly smoothed, prices. The studies also differ in their comparison set and in their definition of stress (Table 1), so they would disagree even if they studied the same market history.

## 3.5 Proposed solutions

**Tests that could prove the framework wrong.** No estimation is done here, but the framework specifies tests that would settle the disagreement rather than add one more estimate to it.

- *Split the 2008 beta between the two channels.* Compare the four Lehman-swap bonds with other CAT bonds from September to December 2008. A gap between the two groups measures the collateral channel. A fall common to all bonds, larger for bonds with a longer spread duration, measures the premium channel.
- *Measure funding stress directly.* Estimate DCC~t~ = *c*~0~ + *c*~1~·Ext~t~ + *c*~2~·Fund~t~ + *c*~3~·(Ext~t~ × Fund~t~), where Ext~t~ marks extreme equity weeks and Fund~t~ marks weeks of high funding stress, measured for example by the Chicago Fed National Financial Conditions Index or the spread between commercial paper and Treasury bills (the TED spread ended with LIBOR). My framework predicts *c*~3~ > 0 after 2009 as well as before: the correlation rises in extreme weeks only when funding is under stress. The simpler account, in which 2008 was a special case, predicts *c*~3~ = 0 after 2009. March 2020 and September-October 2022 provide the observations.
- *Correct both biases and separate the components.* Desmooth the index, as Feng and Zeng (2025) do, add lagged market returns (Dimson, 1979), and adjust crisis correlations for volatility (Forbes and Rigobon, 2002), or use transaction prices from TRACE, as Herrmann and Hibbeln (2023) do. Using Swiss Re's price return index instead of the total return index removes the collateral yield and the contractual spread, so what is left is mainly −*ℓ*~t~ − *D*·Δ*π*~t~ − *k*~t~.
- *Flag catastrophe weeks.* Weeks with a major catastrophe, such as the landfalls of Ike in 2008 and Ian in 2022, should be identified separately, so that a coincidence of the two shocks is not read as market beta.
- *Separate liquidity from duration.* Less liquid bonds should show larger stress betas, but bonds far from maturity are both less liquid and longer in spread duration. The comparison has to be made between bonds with similar remaining terms.

**Portfolio and market rules that remove what can be removed.** Equation (3) also says which part of the beta can be engineered away.

- *Keep the collateral channel closed.* Collateral should be held in Treasury money-market funds or equivalent instruments in trust, with no bank guaranteeing its value and with the holdings disclosed. Most of the market has moved this way since 2009 (Artemis, 2011), but investors should verify the terms of each issue.
- *Contain the premium channel.* An investor that plans to raise cash by selling CAT bonds in a crisis creates the correlation it bought them to avoid. Funds that promise frequent redemptions should match those terms to the liquidity of their bonds through notice periods, cash buffers or redemption limits, and the allocation should be small enough that it never has to be sold in a crisis. Since a premium-driven fall is recovered by a holder who can wait, the investor's own funding decides whether the fall becomes a loss.
- *Limit concentration.* Limits by peril, region and sponsor keep the insurance core diversified within the allocation, which matters since Feng and Zeng (2025) find hedge ratios sensitive to extreme weather.
- *Classify perils honestly.* Pandemic bonds, and other bonds whose peril is itself a macroeconomic shock, should not be presented or modelled as zero-beta exposures.

## 3.6 Conclusion of the analysis

Whether CAT bonds are zero-beta assets depends on which part of the bond the question refers to. Under the assumption that natural catastrophes do not depend on markets, the insurance core is zero-beta. The bond as a traded security has a small beta in calm markets, a beta that can turn positive in a funding crisis through the premium channel, and a beta that turned positive in 2008, when Carayannopoulos and Perez attribute much of the effect to a collateral design the market has since abandoned. On the evidence reviewed, CAT bonds are a reliable diversifier; whether they also qualify as a weak hedge on average is disputed; and their safe-haven property is conditional: at least weak in equity sell-offs, weaker in funding crises, and absent for perils that are themselves macroeconomic shocks.

# 4. Conclusion

This paper asked whether CAT bonds keep their diversification benefits during financial stress. The literature gives three answers: the zero-beta property holds (Carayannopoulos and Perez, 2015, outside crises; Haffar and Le Fur, 2022), it fails (Gürtler et al., 2016; Carayannopoulos and Perez after Lehman's failure), or it depends on the period (Drobetz et al., 2020; Feng and Zeng, 2025).

My contribution is to propose a framework under which these conclusions are consistent. It splits the CAT bond return into an insurance core, which for natural perils is close to independent of markets, and a financial wrapper, whose exposure depends on the collateral structure and on whether a stress episode is a funding crisis. Sorting the evidence into the four regimes of Table 2 accounts for the positive betas of 2007-2009, the safe haven against stocks after the crisis, and the small fall of March 2020 that was described as temporary within weeks. Part of the disagreement is also statistical: quote-based indices bias co-movement toward zero, correlations measured in volatile periods exaggerate the co-movement that exists, and the studies are exposed to these biases in different degrees.

The answer to the research question is therefore conditional. CAT bonds retain their diversification benefit in financial stress when their collateral is safe and their holders are not forced to sell. Under those conditions they can act as a weak safe haven against stocks. They lose part of the benefit when either condition fails. Investors can make the benefit more reliable through collateral rules, liquidity management and concentration limits, but they should treat CAT bonds as a diversifier with a conditional safe-haven property, not as crisis insurance.

The analysis has limits. It rests on published results rather than new estimates, and the grid was built after reading the evidence, so the predictions of Section 3.5 are hypotheses that still need to be tested. The strong post-crisis safe haven found by Drobetz et al. is not explained by the framework. Several post-2009 funding episodes, in 2011-2012 and in 2022, have not been studied separately, so the evidence for the bottom-left cell of Table 2 rests mainly on March 2020. Finally, the framework assumes that catastrophe losses are independent of markets for natural perils. That assumption is a reasonable starting point, but it deserves to be re-examined as pandemic, cyber and climate-related risks take a larger share of the market.

# References

Artemis (2009). "Ajax Re notes downgraded again by S&P after principal not paid in full," *Artemis.bm*, May 12, 2009. https://www.artemis.bm/news/ajax-re-notes-downgraded-again-by-sp-after-principal-not-paid-in-full/

Artemis (2011). "The death of the total return swap and the rise of the Treasury money market fund," *Artemis.bm*, December 19, 2011. https://www.artemis.bm/news/the-death-of-the-total-return-swap-and-the-rise-of-the-treasury-money-market-fund/

Baur, Dirk G., and Brian M. Lucey (2010). "Is gold a hedge or a safe haven? An analysis of stocks, bonds and gold," *The Financial Review*, vol. 45, no. 2, p. 217–229. https://doi.org/10.1111/j.1540-6288.2010.00244.x

Baur, Dirk G., and Thomas K. McDermott (2010). "Is gold a safe haven? International evidence," *Journal of Banking and Finance*, vol. 34, no. 8, p. 1886–1898. https://doi.org/10.1016/j.jbankfin.2009.12.008

Bouri, Elie, Peter Molnár, Georges Azzi, David Roubaud, and Lars Ivar Hagfors (2017). "On the hedge and safe haven properties of Bitcoin: Is it really more than a diversifier?" *Finance Research Letters*, vol. 20, p. 192–198. https://doi.org/10.1016/j.frl.2016.09.025

Braun, Alexander (2016). "Pricing in the primary market for cat bonds: New empirical evidence," *Journal of Risk and Insurance*, vol. 83, no. 4, p. 811–847. https://doi.org/10.1111/jori.12067

Brunnermeier, Markus K., and Lasse Heje Pedersen (2009). "Market liquidity and funding liquidity," *Review of Financial Studies*, vol. 22, no. 6, p. 2201–2238. https://doi.org/10.1093/rfs/hhn098

Campbell, John Y., and Tuomo Vuolteenaho (2004). "Bad beta, good beta," *American Economic Review*, vol. 94, no. 5, p. 1249–1275. https://doi.org/10.1257/0002828043052240

Carayannopoulos, Peter, and M. Fabricio Perez (2015). "Diversification through catastrophe bonds: Lessons from the subprime financial crisis," *The Geneva Papers on Risk and Insurance – Issues and Practice*, vol. 40, no. 1, p. 1–28. https://doi.org/10.1057/gpp.2014.14

Cummins, J. David (2008). "CAT bonds and other risk-linked securities: State of the market and recent developments," *Risk Management and Insurance Review*, vol. 11, no. 1, p. 23–47. https://doi.org/10.1111/j.1540-6296.2008.00127.x

Cummins, J. David, and Mary A. Weiss (2009). "Convergence of insurance and financial markets: Hybrid and securitized risk-transfer solutions," *Journal of Risk and Insurance*, vol. 76, no. 3, p. 493–545. https://doi.org/10.1111/j.1539-6975.2009.01311.x

Dimson, Elroy (1979). "Risk measurement when shares are subject to infrequent trading," *Journal of Financial Economics*, vol. 7, no. 2, p. 197–226. https://doi.org/10.1016/0304-405X(79)90013-8

Drobetz, Wolfgang, Henning Schröder, and Lars Tegtmeier (2020). "The role of catastrophe bonds in an international multi-asset portfolio: Diversifier, hedge, or safe haven?" *Finance Research Letters*, vol. 33, article 101198. https://doi.org/10.1016/j.frl.2019.05.016

Duffie, Darrell (2010). "Presidential address: Asset price dynamics with slow-moving capital," *Journal of Finance*, vol. 65, no. 4, p. 1237–1267. https://doi.org/10.1111/j.1540-6261.2010.01569.x

Feng, Chi, and Xudong Zeng (2025). "The Covid-19 pandemic and the portfolio diversification effect of catastrophe bonds," *Journal of Risk*, vol. 27, no. 4, p. 85–112. https://doi.org/10.21314/JOR.2024.022

Forbes, Kristin J., and Roberto Rigobon (2002). "No contagion, only interdependence: Measuring stock market comovements," *Journal of Finance*, vol. 57, no. 5, p. 2223–2261. https://doi.org/10.1111/0022-1082.00494

Froot, Kenneth A. (2001). "The market for catastrophe risk: A clinical examination," *Journal of Financial Economics*, vol. 60, nos. 2–3, p. 529–571. https://doi.org/10.1016/S0304-405X(01)00052-6

Getmansky, Mila, Andrew W. Lo, and Igor Makarov (2004). "An econometric model of serial correlation and illiquidity in hedge fund returns," *Journal of Financial Economics*, vol. 74, no. 3, p. 529–609. https://doi.org/10.1016/j.jfineco.2004.04.001

Government Actuary's Department (2021). "Pandemic bonds: What are they and how do they work?" *GAD blog*, March 2, 2021. https://actuaries.blog.gov.uk/2021/03/02/pandemic-bonds-what-are-they-and-how-do-they-work/

Gürtler, Marc, Martin Hibbeln, and Christine Winkelvos (2016). "The impact of the financial crisis and natural catastrophes on CAT bonds," *Journal of Risk and Insurance*, vol. 83, no. 3, p. 579–612. https://doi.org/10.1111/jori.12057

Haffar, Adlane, and Éric Le Fur (2022). "Dependence structure of CAT bonds and portfolio diversification: A copula-GARCH approach," *Journal of Asset Management*, vol. 23, no. 4, p. 297–309. https://doi.org/10.1057/s41260-022-00271-3

Herrmann, Markus, and Martin Hibbeln (2023). "Trading and liquidity in the catastrophe bond market," *Journal of Risk and Insurance*, vol. 90, no. 2, p. 283–328. https://doi.org/10.1111/jori.12407

Insurance Insider ILS (2020). "Cat bond prices limit Covid-19 fall to under 1%," *Insurance Insider ILS*, March 2020. https://www.insuranceinsiderils.com/article/2876fhy9ajjsuvp26rkuq/cat-bond-prices-limit-covid-19-fall-to-under-1

The Insurer (2020). "Cat bonds nudge up after temporary Covid-19 sell-off," *The Insurer*, May 2020. https://theinsurer.com/analysis/cat-bonds-nudge-up-after-temporary-covid-19-sell-off
