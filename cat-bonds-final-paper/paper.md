---
title: "Are Catastrophe Bonds Really Zero-Beta Assets? Diversification Benefits in Normal Markets and Financial Crises"
author: "Tran Nguyen Quoc-Long"
---

# 1. Introduction

A catastrophe (CAT) bond lets an insurer, a reinsurer or a government pass part of its exposure to natural disasters to capital-market investors. The sponsor pays a premium, the investors put up principal that is held as collateral, and if a specified hurricane, earthquake or other event occurs before maturity, part or all of that principal goes to the sponsor (Cummins, 2008). Froot (2001) showed that catastrophe reinsurance in the 1990s was priced far above expected losses and traced the gap to frictions in the supply of reinsurance capital. Securitization opened catastrophe risk to investors with far more capital, and the market grew accordingly: outstanding CAT bond risk capital rose from about $2.2 billion in 2002 to $23 billion in June 2017 (Drobetz et al., 2020).

To attract those investors, the market offered a simple argument. Whether a hurricane hits Florida or an earthquake hits Tokyo does not depend on the stock market, so the losses on a CAT bond should be unrelated to the losses on stocks and corporate bonds. In CAPM terms, CAT bonds would be zero-beta assets. Their spread over the risk-free rate should then do little more than cover expected losses, and any spread above that level would be an attractive reward for a risk that adds nothing to the systematic risk of a diversified portfolio.

The argument concerns the natural event, while the investor holds a financial security. A CAT bond is a contract with a special purpose vehicle, its principal sits in a collateral account, its price comes from dealer quotes, and it is held by funds that may need cash at the same moment as everyone else. Each of these features can carry financial stress into the bond when no catastrophe has happened. Whether they do so is an empirical question, and the published answers contradict each other.

Three positions can be distinguished. Haffar and Le Fur (2022) support the zero-beta view: in their sample, CAT bonds add the least to the probability of extreme joint movements with an equity portfolio. Carayannopoulos and Perez (2015) and Gürtler, Hibbeln and Winkelvos (2016) reject it: CAT bond returns became correlated with the stock market after the collapse of Lehman Brothers, and CAT bond premiums move with corporate bond spreads. Drobetz, Schröder and Tegtmeier (2020) also conclude that CAT bonds do not behave like a zero-beta investment, but they find that CAT bonds acted as a safe haven against extreme stock market declines after the financial crisis, a result that Feng and Zeng (2025) extend to the COVID-19 period. In this third position the answer depends on the period.

The difference matters for an investor. A diversifier lowers the variance of a portfolio on average. A safe haven holds up when the rest of the portfolio is in a crash. An investor who buys CAT bonds for the second property when they only have the first is exposed at the worst moment.

My research question is: **to what extent do CAT bonds retain their diversification benefits during financial stress, and why do published studies reach different answers?** I argue that the disagreement has little to do with whether catastrophes occur and much to do with how catastrophe risk is collateralised, priced and measured. It comes from four sources: the property being tested (diversifier, hedge or safe haven), the collateral structure in force during the sample, the type of stress (a shortage of funding or a fall in equity prices), and the way CAT bond returns are measured. As my personal contribution, I propose a decomposition of the CAT bond return into an insurance core, whose losses are independent of markets for natural perils, and a financial wrapper, whose market exposure changes with the bond's structure and with the stress episode. The decomposition sorts the samples of the three articles into four regimes, makes predictions that can be tested, and leads to proposals for investors.

Section 2 explains how CAT bonds work, defines the three properties that the literature tests, presents the three articles in detail and adds the studies that diverge from them. Section 3 contains my analysis: the decomposition, the four regimes, the measurement problems and the proposed solutions. Section 4 concludes.

# 2. Literature review

## 2.1 How a CAT bond works, and where financial risk can enter

A sponsor sets up a special purpose vehicle (SPV) that sells notes to investors and signs a reinsurance contract with the sponsor. The proceeds of the notes are placed in a collateral trust account. Investors receive a floating coupon, a money-market rate plus a risk premium, and the bonds usually mature in three to four years (Drobetz et al., 2020). If a qualifying event occurs, the collateral is released to the sponsor and investors lose part or all of their principal. The trigger can be the sponsor's own losses, an industry loss index, a modelled loss or a physical parameter such as wind speed (Cummins, 2008; Cummins and Weiss, 2009).

Several parts of this structure have nothing to do with nature. One is the **collateral**. Before 2009, the vast majority of CAT bonds used a total return swap: an investment bank converted the return on the collateral into a money-market rate and was supposed to absorb changes in the value of the collateral. The collateral itself often had much longer maturities than the bond and could include highly rated asset-backed and mortgage-backed securities, with little monitoring and no obligation for the swap counterparty to keep its value above a threshold (Carayannopoulos and Perez, 2015). Lehman Brothers Special Financing was the swap counterparty for four CAT bonds: Ajax Re, Carillon, Newton Re and Willow Re. When Lehman failed in September 2008, these bonds were downgraded and their collateral lost value. Ajax Re paid all its interest but could not repay its principal in full at maturity in May 2009 (Artemis, 2009). After issuance froze in late 2008, new deals restricted collateral to cash, government-guaranteed bank debt, U.S. Treasury money-market funds and putable notes from sovereign or quasi-governmental issuers, with frequent mark-to-market and trustee monitoring (Carayannopoulos and Perez, 2015). No new CAT bond used a total return swap after 2009, and by the end of 2011 Treasury money-market funds accounted for more than 60 percent of collateral structures (Artemis, 2011).

Another is **liquidity**. CAT bonds trade over the counter and not very often. Using 9,393 secondary-market trades reported to TRACE between 2015 and 2019, Herrmann and Hibbeln (2023) find that liquidity is lower for riskier bonds and for bonds far from maturity, and they estimate that the liquidity premium accounts for about a fifth of the observed CAT bond yield spread. A premium of that size can move when dealers and investors run short of capital, which is also when stock prices fall (Brunnermeier and Pedersen, 2009). In late 2008, distressed CAT bonds were put up for sale quickly in a market drained of liquidity, and investors suffered losses "not from natural catastrophic events, but from market risks that they thought they had been isolated from" (Carayannopoulos and Perez, 2015, p. 22-23).

Measurement is a further source of difference. The three articles use two Swiss Re indices, which are built from secondary-market bid indications rather than trades (Drobetz et al., 2020), and the net asset value of a CAT bond fund. An index of quotes can be smoothed, which lowers its measured volatility and its correlation with other markets (Getmansky, Lo and Makarov, 2004).

## 2.2 Diversifier, hedge and safe haven: what each test measures

The articles reviewed here use, explicitly or not, the definitions of Baur and Lucey (2010). A **hedge** is an asset that is uncorrelated or negatively correlated with another asset or portfolio on average. A **diversifier** is positively, but not perfectly, correlated with it on average. A **safe haven** is uncorrelated or negatively correlated with it during extreme market declines. Baur and McDermott (2010) distinguish strong and weak versions: a strong hedge or safe haven is negatively correlated with the market, a weak one is uncorrelated. In this terminology, an asset whose beta is zero on average is a weak hedge, which is a stronger property than being a diversifier.

The zero-beta claim, which says the beta is zero at all times, amounts to "weak hedge plus weak safe haven", so evidence of diversification does not confirm it. The definitions are also about correlation, not price: a statistical safe haven can lose money in a crash as long as its losses do not move with the market's.

The word "strong" also changes meaning between studies. In the regression test used by Drobetz et al. (2020), described in Section 2.4, a strong safe haven is an asset whose correlation falls significantly during extreme weeks. That does not require the correlation in those weeks to be negative, as Baur and McDermott's definition does.

The tools differ as well. A beta divides the covariance with the market by the market's variance, a correlation scales the same covariance by both volatilities, and a copula describes dependence separately from the individual distributions, including in the tails. They can give different verdicts on the same data (Section 3.4).

## 2.3 Carayannopoulos and Perez (2015): zero beta, except in a crisis

The first article asks whether CAT bonds are zero-beta investments and whether they diversify a portfolio. The authors use 614 weekly returns, from January 2002 to October 2013, on the Swiss Re BB CAT bond price index, the S&P 500, an investment-grade U.S. corporate bond index and a 5-to-7-year government bond index. They estimate time-varying covariances with a diagonal-VEC multivariate GARCH model, identify high- and low-correlation regimes with a Markov-switching model, and compute dynamic hedge ratios, the conditional covariance with the S&P 500 divided by its conditional variance, which they read as time-varying betas. The crisis is the NBER period from December 2007 to May 2009.

Simple correlations already show the pattern. The correlation between CAT bonds and the S&P 500 is 0.016 before the crisis, 0.252 during it (significant at 5 percent) and 0.058 after it; with corporate bonds it goes from 0.003 to 0.475 and back to 0.092. The dynamic estimates add the timing. The correlation with the stock market stayed close to zero until the end of August 2008, rose from September 2008 to 0.24 in May 2009, fluctuated widely through 2010, and returned to its pre-crisis level at the beginning of 2011. The high-correlation regime that began in October 2008 lasted about 30 months; those after Katrina, the 2011 Japanese earthquake and Sandy were much shorter. The economic size of the effect was small. The CAT bond beta peaked at 0.014 in January 2010, against 0.13 for corporate bonds, and the weekly volatility of CAT bonds barely moved (0.37 percent before the crisis, 0.41 percent during it) while that of the S&P 500 rose from 1.91 to 4.49 percent. The authors conclude that CAT bonds "are not zero-beta assets" (p. 21), that weaknesses of the trust accounts were the main cause, and that CAT bonds remain a valuable diversifier because the crisis affected them far less than other assets.

The strength of the article is that it treats beta as a variable and dates the change precisely. The date matters: the first nine months of the recession, including the funding strains around Bear Stearns in March 2008, left the correlation near zero, and the jump came only when Lehman's failure hit the swap structures. Its limit, for my question, is that a beta estimated on returns cannot say which part of the bond moved with the market. A fall in the value of Lehman-guaranteed collateral and a rise in the premium demanded by investors who needed cash both appear as a positive beta, and the authors' own account of the crisis describes both. Timing adds a further difficulty, since Hurricane Ike struck Texas in the same month as Lehman's failure. The authors discuss the coincidence and argue, by comparison with Katrina, the Japanese earthquake and Sandy, that Ike alone cannot explain the size and persistence of the 2008 correlation; they treat Ike as a catalyst. The comparison is reasonable, but it is not a formal separation of the two shocks.

## 2.4 Drobetz, Schröder and Tegtmeier (2020): a diversifier, and a safe haven only after the crisis

The second article widens the comparison to an international multi-asset portfolio. The authors pair the Swiss Re Global Unhedged CAT Bond Performance Index with total return indices for world stocks (MSCI World IMI), global government bonds (J.P. Morgan GBI Broad), listed real estate (GPR 250), commodities (CRB), listed private equity (LPX 50) and infrastructure (NMX 30). They use 885 weekly returns from January 2002 to December 2018, split into a pre-crisis period (2002-2008) and a post-crisis period (2009-2018). Following Bouri et al. (2017), they first estimate dynamic conditional correlations (DCC) between CAT bonds and each asset class, then regress them on dummies for the weeks in which the other asset's return falls below its 10, 5 and 1 percent quantiles: DCC~t~ = *m*~0~ + *m*~1~·D~10%~ + *m*~2~·D~5%~ + *m*~3~·D~1%~. A significantly positive *m*~0~ makes CAT bonds a diversifier, a zero (negative) *m*~0~ a weak (strong) hedge. Insignificant dummy coefficients make them a weak safe haven, significantly negative ones a strong safe haven.

The constant *m*~0~ is positive and significant at 1 percent for every asset class: about 0.11 with stocks over the full period, 0.24 before 2009 and 0.10 after. CAT bonds are therefore a diversifier, not a hedge. Before 2009 several dummy coefficients are positive, including 0.072 for the 5 percent stock quantile, so the correlation rose in extreme weeks. After 2009 only one coefficient is negative and significant: *m*~2~ for stocks, −0.091 at the 10 percent level, or −0.101 at the 5 percent level with desmoothed returns. On this coefficient rests the conclusion that CAT bonds are a strong safe haven against extreme stock market declines only in the post-crisis period. The authors also conclude that CAT bonds are "not immune to changes in systematic risk" and that their behaviour "is not consistent with a zero-beta investment" (p. 5).

This article is the closest to my question because it separates the three properties and tests them by sub-period. Three features matter for the interpretation. The post-crisis "strong" safe haven rests on one coefficient out of three, and the implied correlation in those weeks is about 0.10 − 0.09 ≈ 0.01, which is a weak safe haven in Baur and McDermott's terms. The pre-crisis period ends in December 2008, so it contains the months after Lehman's failure. And the dummies identify stress through the other asset's return only, so a week of falling stock prices with working funding markets and a week of forced selling are treated alike. The authors deal with the smoothing problem directly: re-estimated with desmoothed returns, their estimates "remain virtually unchanged" (p. 5).

## 2.5 Haffar and Le Fur (2022): little extreme co-movement

The third article studies the dependence structure. Its CAT bond series is not an index but a CAT bond fund, the GAMSTAR Institutional USD Acc share class managed by GAM, whose monthly returns are compared with six stock indices (CAC 40, DJIA, EURO STOXX 50, FTSE 100, Hang Seng, Nikkei 225) over 100 months, from November 2011 to February 2020. The authors model each series with an ARMA-GARCH process and join them with a Student-t copula with asymmetric dynamic conditional correlation. They then compare risk-adjusted performance, contributions to the portfolio's value-at-risk and expected shortfall, co-moments with an equally weighted benchmark portfolio of the other assets, and mean-variance optimal portfolios. They present the paper as the first to use copulas for CAT bonds.

Their findings are the most favourable of the three. The fund has the highest modified Sharpe ratio (0.112, against 0.027 to 0.089 for the stock indices). Its beta with the benchmark portfolio is 0.031, against 0.77 to 1.27 for the stock indices, and its "beta co-kurtosis" is 0.015, against 0.80 to 1.35. Its contribution to the portfolio's 99 percent value-at-risk is negative (−0.54 percent). From the co-kurtosis result, the authors conclude that CAT bonds are the asset that raises the probability of extreme co-variations with the benchmark portfolio the least.

The result has limits that the article itself documents. The extreme co-movement finding comes from co-kurtosis betas, not from a copula tail-dependence coefficient, and the copula's correlation dynamics are weakly identified: the estimated *a* parameter is zero, which the authors note is inconsistent with their test of dynamic correlation. The performance advantage is not statistically distinct, since their peer-performance test gives a 98 percent probability that the fund performs equally to the stock indices, and their most-diversified portfolio gives the fund a zero weight. The alternatives are six stock indices, which depend strongly on each other and on an equity benchmark by construction, so ranking first among them is a modest test. Most important for my question, the sample begins in November 2011 and ends on 28 February 2020, days before the March 2020 sell-off. It contains no funding crisis and no collateral failure.

## 2.6 Other studies: divergent and supporting evidence

Two studies of CAT bond prices take the opposite side. Gürtler et al. (2016) find that the financial crisis and Hurricane Katrina both had a significant effect on secondary-market premiums, and that premiums are positively related to corporate bond spreads, a link that grew stronger during the crisis; they conclude that CAT bonds should not be regarded as zero-beta securities. Braun (2016) finds that the spreads of comparably rated corporate bonds help explain CAT bond spreads at issuance. Both studies show that the price investors demand for catastrophe risk moves with the price of credit risk.

A recent study supports the favourable view for a later crisis. Applying a DCC-GARCH model to a multi-asset portfolio before and during the COVID-19 pandemic, Feng and Zeng (2025) find that CAT bonds were a diversifier over the whole sample and a safe haven against stocks and private equity after the outbreak. The results hold with desmoothed returns, but the authors also find that hedge ratios are sensitive to extreme weather events.

The same period produced a case in which the zero-beta argument fails by design. The World Bank's 2017 pandemic bonds put 16.67 percent of the principal of the Class A notes and all of the principal of the Class B notes at risk if a qualifying pandemic occurred (Government Actuary's Department, 2021), and COVID-19 met the trigger conditions during the same shock that hit equity markets.

Table 1 compares the three main articles.

**Table 1. The three articles compared**

| | Carayannopoulos and Perez (2015) | Drobetz, Schröder and Tegtmeier (2020) | Haffar and Le Fur (2022) |
|:--|:--|:--|:--|
| Question | Are CAT bonds zero-beta, and did the subprime crisis change this? | Are CAT bonds a diversifier, a hedge or a safe haven? | How do CAT bonds depend on equity markets, including in the extremes? |
| Data | Swiss Re BB CAT bond price index vs S&P 500, corporate and government bonds; 614 weekly returns, Jan. 2002 to Oct. 2013 | Swiss Re Global Unhedged index vs six asset classes; 885 weekly returns, Jan. 2002 to Dec. 2018 | GAMSTAR CAT bond fund vs six stock indices; 100 monthly returns, Nov. 2011 to Feb. 2020 |
| Method | Diagonal-VEC MGARCH, Markov switching, dynamic hedge ratios | DCC-GARCH, then regression of the DCC on 10/5/1 percent quantile dummies | Student-t copula with AGDCC; performance, VaR, co-moments, optimal portfolios |
| Stress | NBER crisis, Dec. 2007 to May 2009 | Extreme weeks of the other asset; before vs after 2009 | Co-kurtosis; no crisis in the sample |
| Key results | Correlation with S&P 500: 0.016 / 0.252 / 0.058; beta peaks at 0.014 | Average correlation with stocks 0.24 before 2009, 0.10 after; post-crisis *m*~2~ = −0.091 | Beta 0.031; beta co-kurtosis 0.015; modified Sharpe ratio 0.112 |
| Position on zero beta | Rejected in the crisis, holds outside it | Rejected on average; safe haven against stocks after 2009 | Supported |

# 3. Analysis

## 3.1 What the articles actually disagree about

The contradictions are of two kinds. The first concerns average behaviour. Outside crises, Carayannopoulos and Perez cannot distinguish the correlation of CAT bonds with the stock market from zero, which makes CAT bonds a weak hedge in Baur and Lucey's terms. Drobetz et al. find a positive and significant average correlation, which makes them a diversifier but not a hedge, and Gürtler et al. and Braun find that CAT bond premiums move with corporate spreads. The second and sharper contradiction concerns stress. Carayannopoulos and Perez find that CAT bonds moved with markets after Lehman's failure, and Drobetz et al. find that the correlation rose in extreme weeks before 2009. Drobetz et al. find a safe haven against stocks after 2009, Feng and Zeng after the COVID-19 outbreak, and Haffar and Le Fur find the weakest extreme co-movement of all the assets they study.

The numbers show that the disagreement is smaller than the labels suggest. Every study finds small exposures, with betas of 0.014 (Carayannopoulos and Perez) and 0.031 (Haffar and Le Fur). The studies disagree mainly on whether a small but significant exposure contradicts the zero-beta claim, and on whether 2008 tells us anything about later crises. A simple account would call 2008 a special case and the rest a matter of method. My argument is that the bonds changed, the crises differed and the methods differed, and that a decomposition can separate the three and make a prediction the simple account does not make (Section 3.5).

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

Under this assumption, the measured beta of a natural-catastrophe bond is the beta of its financial wrapper. I call the first term the **premium channel** and the second the **collateral channel**. When markets fall, the required premium rises (*β*~π~ < 0) and collateral losses, if possible at all, become more likely (*β*~k~ < 0), so both channels push the beta above zero in a crisis. The account of 2008 by Carayannopoulos and Perez contains both: collateral that lost value, and distressed bonds sold into an illiquid market. As in Campbell and Vuolteenaho's (2004) split between cash-flow and discount-rate beta, a price fall caused by a higher premium is recovered as the bond approaches maturity if no catastrophe occurs, so it is a loss mainly for a holder who has to sell.

Two qualifications apply. Carayannopoulos and Perez find shorter high-correlation regimes with the S&P 500 after Katrina, the 2011 Japanese earthquake and Sandy, so *β*~ℓ~ is small rather than exactly zero. And the premium channel is not free of catastrophe risk in every sense, since *π* is the price investors charge for bearing it. What the decomposition separates is the occurrence of catastrophes, which markets do not drive, from the price and the packaging of catastrophe risk, which they can.

Equation (3) leads to the following predictions.

1. In calm markets the collateral channel is closed and the premium moves little, so *β* is small. It need not be exactly zero: the link between CAT premiums and corporate spreads found by Gürtler et al. (2016) and Braun (2016) exists outside crises, which is consistent with the positive average correlation of about 0.10 found by Drobetz et al. (2020) after 2009.
2. The collateral channel is open only when the collateral is exposed to the credit of a financial institution. It was open before 2009 and is close to closed for deals whose collateral is held in Treasury money-market funds or government-backed notes.
3. The premium channel opens when holders of CAT bonds need cash at the moment the market falls. They sell, and dealers short of capital absorb the bonds only at a higher premium. When funding is scarce, market liquidity and funding liquidity reinforce each other (Brunnermeier and Pedersen, 2009), and when capital moves slowly into a market after such a shock, prices fall further than fundamentals justify and then recover gradually (Duffie, 2010). The same channel covers the evidence of Gürtler et al. and Braun: if the capital available to bear catastrophe risk shrinks with financial wealth, its price rises with credit spreads, as Froot's (2001) account of capital-driven pricing predicts.

The decomposition also identifies the case in which the zero-beta claim fails at its root. If the peril is itself a macroeconomic shock, *β*~ℓ~ ≠ 0. For diversification purposes, pandemic bonds, and in my view bonds covering systemic cyber risk, belong to a different asset class from natural-catastrophe bonds.

## 3.3 Four stress regimes

Equation (3) suggests classifying stress episodes on two dimensions: whether the collateral was exposed to bank credit, and whether the episode was a funding crisis, in which investors needed cash, or a fall in equity prices while funding markets kept working. Table 2 places the evidence in this grid.

**Table 2. Stress regimes implied by the decomposition, with the evidence for each**

| | Funding crisis (investors need cash) | Equity sell-off, funding markets working |
|:--|:--|:--|
| **Collateral exposed to bank credit (pre-2009 swap structures)** | Both channels open: beta turns positive. *Evidence:* correlation with the S&P 500 jumps after September 2008 (Carayannopoulos and Perez, 2015); correlation rises in extreme weeks before 2009 (Drobetz et al., 2020). | Only the insurance core is tested: beta close to zero. *Evidence:* correlation near zero until August 2008, through the first nine months of the recession (Carayannopoulos and Perez, 2015). |
| **Collateral in Treasury funds or government-backed notes (post-2009)** | Premium channel only: a small fall, later reversed; at most a weak safe haven. *Evidence:* safe haven against stocks after the COVID-19 outbreak, with desmoothed returns (Feng and Zeng, 2025); March 2020 market reports. | Neither channel open: beta close to zero, weak safe haven. *Evidence:* correlation of about 0.01 in extreme stock weeks after 2009 (Drobetz et al., 2020); beta of 0.031 and the lowest co-kurtosis over 2011-2020 (Haffar and Le Fur, 2022). |

Each of the main results can be placed in one cell. Since the grid was built after reading the evidence, this fit shows compatibility, not proof; Section 3.5 states how the grid could be proved wrong.

The top-left cell contains one episode, the months after Lehman's failure. The timing found by Carayannopoulos and Perez is the strongest evidence for the collateral channel: the recession and its first funding strains left CAT bonds uncorrelated with stocks for nine months, and the correlation jumped only when the swap structures failed. The positive extreme-week coefficients of Drobetz et al. before 2009 belong to the same cell, since their pre-crisis period ends in December 2008. None of the reviewed evidence, however, splits the 2008 beta between the collateral channel and the forced sales that followed.

The bottom-right cell explains the favourable results. After 2009 the collateral channel was closed, and in my reading the stock market declines of the post-crisis period did not bring forced selling on the scale of late 2008, so the premium channel stayed weak. The grid predicts a beta close to zero and a weak safe haven, which is what the numbers show: in the post-crisis extreme stock weeks of Drobetz et al., the correlation falls to about 0.01. Their "strong" label comes from the regression definition and rests on one coefficient, so it does not contradict the grid. The whole sample of Haffar and Le Fur lies in this cell: post-2009 collateral and no funding crisis, ending days before March 2020. Their favourable result is what the grid predicts for that cell, and for the same reason it says nothing about funding crises.

March 2020 is the main test of the bottom-left cell: collateral in Treasury funds combined with a severe scramble for cash. The framework predicts a fall driven by forced sales, no loss on collateral, and a recovery once capital returns. The best evidence is Feng and Zeng's, because it holds with desmoothed returns: CAT bonds remained a safe haven against stocks after the outbreak. Market reports agree: the Swiss Re price return index fell by 0.81 percent in the week to 20 March, with markdowns linked to bulk lists of bonds put up for sale (Insurance Insider ILS, 2020), and by May the sell-off was described as temporary (The Insurer, 2020). Since CAT bonds usually mature in three to four years, their spread duration is of the order of one to two years, so equation (1) turns this 0.81 percent fall into a rise of roughly 40 to 80 basis points in the required premium, of the same order as the liquidity premium estimated by Herrmann and Hibbeln (2023). A bond can thus be a statistical safe haven and still lose money in the week an investor needs to sell it.

Other candidates for this cell are not isolated by the reviewed studies, such as September-October 2022, when the UK pension funds' liability-driven investment crisis coincided with Hurricane Ian's landfall on 28 September, a repeat of the Ike-Lehman coincidence.

## 3.4 Measurement choices that move the answer

Part of the divergence between the articles is statistical. Four choices matter.

The first is **economic versus statistical significance**. CAT bond returns are much less volatile than stock returns, so a significant correlation can go with a tiny beta. In the data of Carayannopoulos and Perez, the crisis correlation of 0.25 goes with a beta that peaked at 0.014: a 20 percent fall in the S&P 500 would have cost a CAT bond investor about 0.3 percent. The zero-beta claim is rejected statistically and close to true economically, and the articles differ partly in which of the two they stress.

The second is **conditioning on volatility**. Suppose the CAT bond return is *β* times the market return plus an independent shock with volatility *σ*~ε~. The correlation is then *ρ* = *β*·*σ*~m~/√(*β*²*σ*~m~² + *σ*~ε~²), which rises with the market's volatility *σ*~m~ whenever *β* > 0 (Forbes and Rigobon, 2002). The weekly volatility of the S&P 500 more than doubled during the crisis in the data of Carayannopoulos and Perez, so part of the rise of the correlation from 0.016 to 0.252 is mechanical. Conditioning on volatility can exaggerate co-movement that exists, but it cannot create it, and their beta, which is free of this bias, did rise.

The third is **smoothing**, which matters less than theory suggests. A smoothed index biases beta and correlation toward zero (Getmansky et al., 2004), but the estimates of Drobetz et al. are virtually unchanged after desmoothing, those of Feng and Zeng hold with desmoothed returns, and the index used by Drobetz et al. has negative first-order autocorrelation (−0.34), whereas smoothing produces positive autocorrelation.

The fourth is the **proxy, frequency and window**, and it matters most. One study uses weekly index returns over a sample that includes 2008, another 100 monthly returns of one fund over a sample that excludes both 2008 and March 2020, which cannot detect what the first detects. The studies also differ in comparison assets and in their definition of stress (Table 1).

## 3.5 Proposed solutions

**Tests that could prove the framework wrong.** No estimation is done here, but the framework specifies tests that would settle the disagreement rather than add one more estimate to it.

- *Split the 2008 beta between the two channels.* Compare the four Lehman-swap bonds with other CAT bonds from September to December 2008. A gap between the two groups measures the collateral channel. A fall common to all bonds, larger for bonds with a longer spread duration, measures the premium channel.
- *Measure funding stress directly.* Estimate DCC~t~ = *c*~0~ + *c*~1~·Ext~t~ + *c*~2~·Fund~t~ + *c*~3~·(Ext~t~ × Fund~t~), where Ext~t~ marks extreme equity weeks and Fund~t~ marks weeks of high funding stress, measured for example by the Chicago Fed National Financial Conditions Index or the spread between commercial paper and Treasury bills (the TED spread ended with LIBOR). My framework predicts *c*~3~ > 0 after 2009 as well as before: the correlation rises in extreme weeks only when funding is under stress. The simple account, in which 2008 was a special case, predicts *c*~3~ = 0 after 2009. March 2020 and September-October 2022 provide the observations.
- *Re-run the favourable design on a sample with a funding crisis.* Estimating the copula and co-kurtosis measures of Haffar and Le Fur on weekly index data that include 2008 and March 2020 would test the grid's prediction of stronger extreme co-movement in funding-crisis weeks.
- *Report betas next to correlations*, adjust crisis correlations for volatility (Forbes and Rigobon, 2002), and use TRACE transaction prices where possible (Herrmann and Hibbeln, 2023).
- *Flag catastrophe weeks and separate liquidity from duration.* Weeks with a major catastrophe, such as Ike in 2008 and Ian in 2022, should enter the regressions as separate dummies, so that a coincidence of shocks is not read as market beta. Less liquid bonds should show larger stress betas, but bonds far from maturity are both less liquid and longer in duration, so comparisons must be made between bonds with similar remaining terms.

**Portfolio and market rules that remove what can be removed.** Equation (3) also says which part of the beta can be engineered away.

- *Keep the collateral channel closed.* Collateral should be limited to Treasury money-market funds or government-backed notes, held in trust, marked to market and disclosed. Most of the market has moved this way since 2009 (Carayannopoulos and Perez, 2015; Artemis, 2011), but investors should verify the terms of each issue.
- *Contain the premium channel.* An investor that plans to raise cash by selling CAT bonds in a crisis creates the correlation it bought them to avoid. Funds that promise frequent redemptions should match those terms to the liquidity of their bonds through notice periods, cash buffers or redemption limits, and the allocation should be small enough never to be sold in a crisis. Since a premium-driven fall is recovered by a holder who can wait, the investor's own funding decides whether it becomes a loss.
- *Limit concentration.* Limits by peril, region and sponsor keep the insurance core diversified within the allocation, which matters since Feng and Zeng (2025) find hedge ratios sensitive to extreme weather.
- *Classify perils honestly.* Pandemic bonds, and other bonds whose peril is itself a macroeconomic shock, should not be presented or modelled as zero-beta exposures.

## 3.6 Conclusion of the analysis

Whether CAT bonds are zero-beta assets depends on which part of the bond the question refers to. If natural catastrophes do not depend on markets, the insurance core is zero-beta. The traded bond has a small positive beta in calm markets, a beta that can rise in a funding crisis through the premium channel, and a beta that rose in 2008 when pre-2009 collateral structures failed, although even then the exposure was economically small. On the evidence reviewed, CAT bonds are a reliable diversifier; whether they also qualify as a weak hedge on average is disputed; and their safe-haven property is conditional: weak in equity sell-offs after 2009, weaker in funding crises, and absent for perils that are themselves macroeconomic shocks.

# 4. Conclusion

This paper asked whether CAT bonds keep their diversification benefits during financial stress. The literature gives three answers: the zero-beta property holds (Haffar and Le Fur, 2022), it fails (Carayannopoulos and Perez, 2015; Gürtler et al., 2016), or it fails on average while CAT bonds still protect against extreme stock market declines in some periods (Drobetz et al., 2020; Feng and Zeng, 2025). My contribution is a framework under which these conclusions are consistent. It splits the CAT bond return into an insurance core, which for natural perils is close to independent of markets, and a financial wrapper, whose exposure depends on the collateral structure and on whether a stress episode is a funding crisis. The samples of the three articles fall into different cells of Table 2: the 2008 crisis with exposed collateral for Carayannopoulos and Perez, a period split around 2009 for Drobetz et al., and a calm post-2009 window for Haffar and Le Fur. Read this way, their results describe different regimes rather than contradicting each other. Part of the disagreement is also statistical: significant correlations go with tiny betas, volatile periods exaggerate measured correlation, and a short monthly sample from a calm period cannot detect what a weekly sample containing 2008 detects.

The answer to the research question is therefore conditional. CAT bonds retain their diversification benefit in financial stress when their collateral is safe and their holders are not forced to sell. Under those conditions they can act as a weak safe haven against stocks. They lose part of the benefit when either condition fails, although even in 2008 the loss was small. Investors can make the benefit more reliable through collateral rules, liquidity management and concentration limits, but they should treat CAT bonds as a diversifier with a conditional safe-haven property, not as crisis insurance.

The analysis has limits. It rests on published results rather than new estimates, and the grid was built after reading the evidence, so the predictions of Section 3.5 still need to be tested. The evidence for the bottom-left cell of Table 2 rests mainly on March 2020. Finally, the framework assumes that catastrophe losses are nearly independent of markets for natural perils. That assumption is a reasonable starting point, but it deserves to be re-examined as pandemic, cyber and climate-related risks take a larger share of the market.

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
