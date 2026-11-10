---
title: "Are Catastrophe Bonds Really Zero-Beta Assets? Diversification Benefits in Normal Markets and Financial Crises"
author: "Tran Nguyen Quoc-Long"
---

# 1. Introduction

A catastrophe (CAT) bond lets an insurer, a reinsurer or a government pass part of its exposure to natural disasters to capital-market investors. The sponsor pays a premium, the investors put up principal that is held as collateral, and if a specified hurricane, earthquake or other event occurs before maturity, part or all of that principal goes to the sponsor (Cummins, 2008). Securitisation opened catastrophe risk to investors with far more capital than reinsurers, and the market grew accordingly: outstanding CAT bond risk capital rose from about $2.2 billion in 2002 to $23 billion in June 2017 (Drobetz et al., 2020).

To attract those investors, the market offered a simple argument. Whether a hurricane hits Florida or an earthquake hits Tokyo does not depend on the stock market, so the losses on a CAT bond should be unrelated to the losses on stocks and corporate bonds. In CAPM terms, CAT bonds would be zero-beta assets, and any spread above expected losses would reward a risk that adds nothing to the systematic risk of a diversified portfolio. The argument concerns the natural event, while the investor holds a financial security: a contract with a special purpose vehicle, whose principal sits in a collateral account, whose price comes from dealer quotes, and which is held by funds that may need cash at the same moment as everyone else. Each of these features can carry financial stress into the bond when no catastrophe has happened, and the published evidence on whether they do is contradictory.

Three positions can be distinguished. Haffar and Le Fur (2022) come closest to the zero-beta view, although they do not test it formally: in their sample, CAT bonds add the least to extreme joint movements with an equity portfolio. Carayannopoulos and Perez (2015) and Gürtler, Hibbeln and Winkelvos (2016) reject it: CAT bond returns became correlated with the stock market after the collapse of Lehman Brothers, and CAT bond premiums move with corporate bond spreads. Drobetz, Schröder and Tegtmeier (2020) also conclude that CAT bonds do not behave like a zero-beta investment. They find, however, that CAT bonds acted as a safe haven against extreme stock market declines after the financial crisis, a result that Feng and Zeng (2025) extend to the COVID-19 period. In this third position the answer depends on the period.

The difference matters for investors and for risk managers. A diversifier lowers the variance of a portfolio on average; a safe haven does not move with the rest of the portfolio in a crash, so an investor who buys CAT bonds for the second property when they only have the first is exposed at the worst moment, and a value-at-risk estimated on calm data understates the risk of the portfolio if the correlation of CAT bonds with stocks rises when stocks fall.

The three articles cannot settle the question as they stand, because they do not measure the same object. They use different series (two Swiss Re indices and one fund), frequencies (weekly and monthly), windows (2002-2013, 2002-2018 and 2011-2020) and definitions of stress (NBER recession dates, extreme weeks of the other asset, and co-kurtosis). None separates a crisis in which the collateral is at risk from one in which investors only need cash. Their conclusions contradict each other; their estimates need not.

My research question is: **to what extent do CAT bonds retain their diversification benefits during financial stress, and why do published studies reach different answers?** I argue that the disagreement has little to do with whether catastrophes occur and much to do with how catastrophe risk is collateralised, priced and measured. My contribution is a decomposition of the CAT bond return into an insurance core, whose losses are nearly independent of markets for natural perils, and a financial wrapper, whose market exposure depends on the collateral structure and on the type of stress. The decomposition sorts the samples of the three articles into four regimes and yields testable predictions and proposals for investors. The answer it gives is conditional: CAT bonds remain a reliable diversifier, but their safe-haven property requires safe collateral and weakens when holders are forced to sell.

The question raises three issues. The first is conceptual: diversifier, hedge, safe haven and zero beta are different properties, and evidence for one does not establish another. The second is economic: a CAT bond can move with the market because its collateral is exposed to a bank or because its holders must sell, and the two causes call for different remedies. The third is statistical: betas, correlations and copulas, estimated on different series and windows, can give different verdicts on the same bonds.

The paper proceeds as follows. Section 2 explains how a CAT bond works and where financial risk can enter it, defines the properties the literature tests, presents the three articles in detail together with the studies that support or contradict them, and ends on what the literature leaves open. Section 3 first assesses how far the evidence of each article goes. It then presents my contribution, the decomposition of the CAT bond return, uses it to sort the evidence into four stress regimes, examines the measurement choices that move the answer, and proposes tests and portfolio rules. Section 4 concludes.

# 2. Literature review

## 2.1 How a CAT bond works, and where financial risk can enter

A sponsor sets up a special purpose vehicle (SPV) that sells notes to investors and signs a reinsurance contract with the sponsor. The proceeds of the notes are placed in a collateral trust account. Investors receive a floating coupon, a money-market rate plus a risk premium, and the bonds usually mature in three to four years (Drobetz et al., 2020). If a qualifying event occurs, the collateral is released to the sponsor and investors lose part or all of their principal. The trigger can be the sponsor's own losses, an industry loss index, a modelled loss or a physical parameter such as wind speed (Cummins, 2008).

Several parts of this structure have nothing to do with nature. One is the **collateral**. Before 2009, the vast majority of CAT bonds used a total return swap: an investment bank converted the return on the collateral into a money-market rate and was supposed to absorb changes in the value of the collateral. The collateral itself often had much longer maturities than the bond and could include highly rated asset-backed and mortgage-backed securities, with little monitoring and no obligation for the swap counterparty to keep its value above a threshold (Carayannopoulos and Perez, 2015). When Lehman Brothers, the swap counterparty of several CAT bonds, failed in September 2008, this structure failed with it. After issuance froze in late 2008, new deals restricted collateral to cash, government-guaranteed bank debt, U.S. Treasury money-market funds and putable notes from sovereign or quasi-governmental issuers, with frequent mark-to-market and trustee monitoring (Carayannopoulos and Perez, 2015).

Another is **liquidity**. CAT bonds trade over the counter and not very often. Using 9,393 secondary-market trades reported to TRACE between 2015 and 2019, Herrmann and Hibbeln (2023) find that liquidity is lower for riskier bonds and for bonds far from maturity, and they estimate that the liquidity premium accounts for about a fifth of the observed CAT bond yield spread: 98 basis points on average and 141 basis points for high-risk bonds. Liquidity is also higher when the whole market trades more, and trading is dominated by brokers who hold no inventory of their own, so few intermediaries stand ready to absorb sales. A premium of that size can move when dealers and investors run short of capital, which is also when stock prices fall (Brunnermeier and Pedersen, 2009). In late 2008, distressed CAT bonds were put up for sale quickly in a market drained of liquidity, and investors suffered losses "not from natural catastrophic events, but from market risks that they thought they had been isolated from" (Carayannopoulos and Perez, 2015, pp. 22-23).

A third is **measurement**. The three articles use two Swiss Re indices, which are built from secondary-market bid indications rather than trades (Drobetz et al., 2020), and the net asset value of a CAT bond fund. An index of quotes can be smoothed, which lowers its measured volatility and its correlation with other markets (Getmansky, Lo and Makarov, 2004).

## 2.2 Diversifier, hedge and safe haven: what each test measures

The articles use, explicitly or not, the definitions of Baur and Lucey (2010). A hedge is uncorrelated or negatively correlated with another asset or portfolio on average. A diversifier is positively, but not perfectly, correlated with it on average. A safe haven is uncorrelated or negatively correlated with it during extreme market declines. Baur and McDermott (2010) add that a strong hedge or safe haven is negatively correlated with the market and a weak one is uncorrelated. The zero-beta claim, which says the beta is zero at all times, therefore amounts to a weak hedge plus a weak safe haven, and evidence of diversification does not confirm it. The definitions are also about correlation, not price: a statistical safe haven can lose money in a crash as long as its losses do not move with the market's.

Two warnings follow. The word "strong" changes meaning between studies: in the regression test of Drobetz et al. (2020), a strong safe haven is an asset whose correlation falls significantly in extreme weeks, not one whose correlation is negative. And the tools differ: a beta divides the covariance with the market by the market's variance, a correlation scales it by both volatilities, and a copula models dependence, including in the tails, separately from each distribution, so they can disagree on the same data (Section 3.4).

## 2.3 Carayannopoulos and Perez (2015): zero beta, except in a crisis

The first article asks whether CAT bonds are zero-beta investments and whether they diversify a portfolio. The authors use 614 weekly returns, from January 2002 to October 2013, on the Swiss Re BB CAT bond price index, the S&P 500, an investment-grade U.S. corporate bond index and a 5-to-7-year government bond index. Swiss Re maintains four insurance-linked securities indices; the authors use the BB price index because the S&P 500 is also a price index, and their results hold with the broad index and with the BB total return index. They estimate time-varying covariances with a diagonal-VEC multivariate GARCH model, identify high- and low-correlation regimes with a Markov-switching model, and compute dynamic hedge ratios, the conditional covariance with the S&P 500 divided by its conditional variance, which they read as time-varying betas. The crisis is the NBER period from December 2007 to May 2009.

Simple correlations already show the pattern. The correlation between CAT bonds and the S&P 500 is 0.016 before the crisis, 0.252 during it (significant at 5 percent) and 0.058 after it; with corporate bonds it goes from 0.003 to 0.475 and back to 0.092. With government bonds, by contrast, it falls from 0.128 to an insignificant 0.054: in the crisis, CAT bonds moved with credit, not with safe fixed income. The dynamic estimates add the timing. The correlation with the stock market stayed close to zero until the end of August 2008, rose from September 2008 to 0.24 in May 2009, fluctuated widely through 2010, and returned to its pre-crisis level at the beginning of 2011. The economic size of the effect was small. The CAT bond beta peaked at 0.014 in January 2010, against 0.13 for corporate bonds, and the weekly volatility of CAT bonds barely moved (0.37 percent before the crisis, 0.41 percent during it) while that of the S&P 500 rose from 1.91 to 4.49 percent.

The regime estimates give the same picture. The high-correlation regime with the stock market that began in October 2008 lasted about 30 months, while those after Katrina, the 2011 Japanese earthquake and Sandy were much shorter. The high-correlation regime with corporate bonds was much less persistent than the one with stocks, and the correlation with government bonds shows no regime change during the crisis; its only jump followed Hurricane Ivan at the end of 2004.

The authors conclude that CAT bonds "are not zero-beta assets" (p. 21), that weaknesses of the trust accounts were the main cause, and that CAT bonds remain a valuable diversifier because the crisis affected them far less than other assets. They also note that Hurricane Ike struck Texas in the same month as Lehman's failure and argue, by comparison with the other events, that Ike acted as a catalyst but cannot explain the size and persistence of the 2008 correlation. They describe the effect of the crisis as temporary, since the correlations return to their pre-crisis levels after it.

## 2.4 Drobetz, Schröder and Tegtmeier (2020): a diversifier, and a safe haven only after the crisis

The second article widens the comparison to an international multi-asset portfolio. The authors pair the Swiss Re Global Unhedged CAT Bond Performance Index with total return indices for world stocks (MSCI World IMI), global government bonds (J.P. Morgan GBI Broad), listed real estate (GPR 250), commodities (CRB), listed private equity (LPX 50) and infrastructure (NMX 30). They use 885 weekly returns from January 2002 to December 2018, split into a pre-crisis period (2002-2008) and a post-crisis period (2009-2018). They first estimate dynamic conditional correlations (DCC), a weekly series of correlations between CAT bonds and each asset class, then regress them on dummies for the weeks in which the other asset's return falls below its 10, 5 and 1 percent quantiles: DCC~t~ = *m*~0~ + *m*~1~·*d*~10%~ + *m*~2~·*d*~5%~ + *m*~3~·*d*~1%~. A significantly positive *m*~0~ makes CAT bonds a diversifier, a zero (negative) *m*~0~ a weak (strong) hedge. Insignificant dummy coefficients make them a weak safe haven, significantly negative ones a strong safe haven.

The constant *m*~0~ is positive and significant at 1 percent for every asset class: about 0.11 with stocks over the full period, 0.24 before 2009 and 0.10 after. CAT bonds are therefore a diversifier against all six asset classes and a hedge against none. Before 2009 several dummy coefficients are positive, including 0.072 for the 5 percent stock quantile, so the correlation rose in extreme weeks. After 2009 only one coefficient is negative and significant: *m*~2~ for stocks, −0.091 at the 10 percent level, or −0.101 at the 5 percent level with desmoothed returns. On this coefficient rests the conclusion that CAT bonds are a strong safe haven against extreme stock market declines only in the post-crisis period; they are a safe haven against none of the other asset classes. The authors conclude that CAT bonds are "not immune to changes in systematic risk" and that their behaviour "is not consistent with a zero-beta investment" (p. 5), and they relate this to the two mechanisms already documented: the weak trust accounts described by Carayannopoulos and Perez (2015) and the dependence of CAT bond premiums on corporate spreads found by Gürtler et al. (2016).

The summary statistics show the two faces of the asset. The CAT bond index has the lowest weekly volatility of the seven series (0.76 percent) but the highest kurtosis (313.5) and a strongly negative skewness (−9.0), the mark of rare but large event losses. Its first-order autocorrelation is significantly negative (−0.34), which the authors attribute to the indicative pricing of the index; they re-estimate every regression on desmoothed returns and find the estimates "virtually unchanged" (p. 5).

## 2.5 Haffar and Le Fur (2022): little extreme co-movement

The third article studies the dependence structure. Its CAT bond series is not an index but a CAT bond fund, the GAMSTAR Institutional USD Acc share class managed by GAM, whose monthly returns are compared with six stock indices (CAC 40, DJIA, EURO STOXX 50, FTSE 100, Hang Seng, Nikkei 225) over 100 months, from November 2011 to February 2020. The fund holds 92 percent fixed income and 8 percent cash and is benchmarked against euro government bonds; the paper dates its launch to 26 March 2012. The authors model each series with an ARMA-GARCH process and join them with a Student-t copula with asymmetric dynamic conditional correlation. They then compare risk-adjusted performance, contributions to the portfolio's value-at-risk and expected shortfall, co-moments with an equally weighted benchmark portfolio of the other assets, and mean-variance optimal portfolios. They present the paper as the first to use copulas for CAT bonds.

Their findings are the most favourable of the three. The fund has the highest modified Sharpe ratio (0.112, against 0.027 to 0.089 for the stock indices). Its beta with the benchmark portfolio is 0.031, against 0.77 to 1.27 for the stock indices, and its "beta co-kurtosis" is 0.015, against 0.80 to 1.35. Its contribution to the portfolio's 99 percent value-at-risk is negative (−0.54 percent). From the co-kurtosis result, the authors conclude that CAT bonds are the asset that raises the probability of extreme co-variations with the benchmark portfolio the least.

The authors also report results that temper these findings. In the marginal models, the GARCH parameters are almost always jointly insignificant, and the DCC parameter *a* of the copula is estimated at zero, which they note is inconsistent with their test of dynamic correlation. Their peer-performance test gives a 98 percent probability that the fund performs equally to the stock indices, and their most-diversified portfolio gives the fund a zero weight. They read their own beta cautiously: there is "a slight positive beta co-variance", so adding the fund to the benchmark portfolio "will not reduce its volatility" (pp. 304-305). They nevertheless cite Carayannopoulos and Perez (2015) in support (p. 298) and conclude that their results "confirm those of previous studies" (p. 307).

## 2.6 Other studies: divergent and supporting evidence

Two studies of CAT bond prices take the opposite side. Gürtler et al. (2016) find that the financial crisis and Hurricane Katrina both had a significant effect on secondary-market premiums, and that premiums are positively related to corporate bond spreads, a link that grew stronger during the crisis; they conclude that CAT bonds should not be regarded as zero-beta securities. Braun (2016) finds that the spreads of comparably rated corporate bonds help explain CAT bond spreads at issuance. Both show that the price investors demand for catastrophe risk moves with the price of credit risk.

A recent study supports the favourable view for a later crisis. Applying a DCC-GARCH model to an international portfolio of stocks, private equity, infrastructure and commodities before and during the COVID-19 pandemic, Feng and Zeng (2025) find that CAT bonds were a diversifier over the whole sample and a safe haven against stocks and private equity after the outbreak. The results hold under alternative specifications, including desmoothed returns. Two findings point the other way: hedge ratios, although low, are sensitive to extreme weather events, and the correlation with commodities became asymmetric during the pandemic, with stronger co-movement in falling markets. Table 1 summarises the three main articles.

**Table 1. The three articles compared**

| | Carayannopoulos and Perez (2015) | Drobetz, Schröder and Tegtmeier (2020) | Haffar and Le Fur (2022) |
|:--|:--|:--|:--|
| Question | Are CAT bonds zero-beta, and did the subprime crisis change this? | Are CAT bonds a diversifier, a hedge or a safe haven? | How do CAT bonds depend on equity markets, including in the extremes? |
| Data | Swiss Re BB price index vs S&P 500, corporate and government bonds; 614 weekly returns, 2002-2013 | Swiss Re Global Unhedged index vs six asset classes; 885 weekly returns, 2002-2018 | GAMSTAR CAT bond fund vs six stock indices; 100 monthly returns, Nov. 2011 to Feb. 2020 |
| Method | Diagonal-VEC MGARCH, Markov switching, dynamic hedge ratios | DCC-GARCH, then regression of the DCC on 10/5/1 percent quantile dummies | Student-t copula with asymmetric DCC; performance, VaR, co-moments |
| Stress | NBER crisis, Dec. 2007 to May 2009 | Extreme weeks of the other asset; before vs after 2009 | Co-kurtosis; no crisis in the sample |
| Key results | Correlation with S&P 500 before / during / after: 0.016 / 0.252 / 0.058; beta peaks at 0.014 | Average correlation with stocks 0.24 before 2009, 0.10 after; post-crisis *m*~2~ = −0.091 | Beta 0.031; beta co-kurtosis 0.015; modified Sharpe ratio 0.112 |
| Zero beta | Rejected in the crisis, holds outside it | Rejected on average; safe haven against stocks after 2009 | Closest to zero beta (not tested formally) |

Source: compiled by the author from the three articles.

## 2.7 What the literature agrees on, and what it leaves open

The studies agree that CAT bonds diversify stock portfolios and have low volatility and small betas. Their contradictions are of two kinds. The first concerns average behaviour: outside crises, Carayannopoulos and Perez cannot distinguish the correlation with the stock market from zero, a weak hedge, while Drobetz et al. find a positive and significant average correlation, a diversifier but not a hedge, and Gürtler et al. and Braun find that premiums move with corporate spreads. The second and sharper contradiction concerns stress: CAT bonds moved with markets after Lehman's failure and in extreme weeks before 2009, but Drobetz et al. find a safe haven after 2009, Feng and Zeng after the COVID-19 outbreak, and Haffar and Le Fur the weakest extreme co-movement of all the assets they study. Haffar and Le Fur see no contradiction, because their question is diversification; the disagreement appears only when the question is the zero-beta property.

What the literature leaves open is why the answer changes. No study separates a loss on collateral from a fall in price driven by liquidity, and none conditions on the type of stress: NBER dates, extreme weeks of the other asset and a pre/post-outbreak split all treat a funding crisis and an equity sell-off alike. Section 3 addresses that gap.

# 3. Analysis

## 3.1 How far the evidence of each article goes

Each article answers its own question; none answers the question of this paper on its own. The strength of Carayannopoulos and Perez is that they treat beta as a variable and date the change: the correlation stayed near zero through the first nine months of the recession and jumped only when Lehman's failure hit the swap structures. Their limit is that a beta estimated on returns cannot say which part of the bond moved: a fall in the value of Lehman-guaranteed collateral and a rise in the premium demanded by investors who needed cash both appear as a positive beta, and their own account of 2008 describes both. Their treatment of Hurricane Ike is an argument by comparison, not a formal separation of the two shocks.

Drobetz et al. come closest to my question, but three features limit their safe-haven result. It rests on one coefficient out of three, and the arithmetic of their own model gives a weaker picture: because the dummies are nested, the implied correlation in the worst 5 percent of post-crisis weeks is about 0.05, or 0.01 if the insignificant *m*~1~ is set to zero, and in the worst 1 percent of weeks the point estimates add up to about 0.15, above the 0.10 of ordinary weeks.[^nested] This is at most a weak safe haven in Baur and McDermott's terms, not a strong one. Second, the pre-crisis period ends in December 2008, so it contains the months after Lehman's failure. Third, the dummies identify stress by the other asset's return only, so they cannot tell an equity sell-off from a funding crisis.

Haffar and Le Fur's favourable result has the narrowest base. It rests on co-kurtosis betas rather than a copula tail-dependence coefficient, the copula adds little since its correlation dynamics are not identified, and the performance advantage is not statistically distinct (Section 2.5). Ranking first among six stock indices that are strongly correlated with each other and with the equity benchmark is a modest test. The fund series mixes CAT bond risk with a manager's choices and, by the paper's own dates, begins four months before the fund was launched. Above all, the sample ends days before the March 2020 sell-off and contains no funding crisis and no collateral failure.

The disagreement is therefore smaller than the labels suggest. With betas of 0.014 at the 2010 peak and 0.031 in calm years, the studies disagree mainly on whether a small but significant exposure contradicts the zero-beta claim, and on whether 2008 says anything about later crises. A simple account would call 2008 a special case. My argument is that the bonds changed, the crises differed and the methods differed, and that a decomposition separates the first two and makes a prediction the simple account does not (Section 3.5).

## 3.2 My contribution: a decomposition of the CAT bond return

I write the return of a CAT bond, or of an index of CAT bonds, over one period as

::: {custom-style="Equation"}
*R*~t~ = *r*~t~ + *s* − *ℓ*~t~ − *D*·Δ*π*~t~ − *k*~t~	(1)
:::

where *r*~t~ is the return on the collateral, *s* is the contractual spread accrued over the period, *ℓ*~t~ is the loss caused by catastrophes (a realised loss, or a revaluation of the expected loss after an event), Δ*π*~t~ is the change in the premium *π* that investors require above the expected loss, *D* is the bond's spread duration, and *k*~t~ is the collateral loss caused by a counterparty failure or a fall in the value of the collateral assets. Defining *π* net of the expected loss keeps a revision of the expected loss in *ℓ*~t~ only. The insurance core is *s* − *ℓ*~t~ and the financial wrapper is *r*~t~ − *D*·Δ*π*~t~ − *k*~t~.

The beta of the bond with respect to the market return *R*~m~ is then the sum of the betas of its components, *β*~x~ = Cov(*x*~t~, *R*~m,t~)/Var(*R*~m,t~), where *β*~π~ is the beta of Δ*π*~t~:[^betasum]

::: {custom-style="Equation"}
*β* = *β*~r~ − *β*~ℓ~ − *D*·*β*~π~ − *β*~k~	(2)
:::

The zero-beta argument is an assumption about *ℓ*~t~ only: natural catastrophes do not depend on financial markets, so *β*~ℓ~ = 0. The collateral earns a short-term money-market rate whose weekly variation is negligible, so *β*~r~ ≈ 0. What is left is

::: {custom-style="Equation"}
*β* ≈ −*D*·*β*~π~ − *β*~k~	(3)
:::

Under this assumption, the measured beta of a natural-catastrophe bond is the beta of its financial wrapper. I call the first term the premium channel and the second the collateral channel. When markets fall, the required premium rises (*β*~π~ < 0) and collateral losses, if possible at all, become more likely (*β*~k~ < 0); each term is then a minus sign in front of a negative number, so both push the beta above zero in a crisis. The two channels differ in cost: a fall caused by a higher premium is recovered by maturity if no catastrophe occurs, so it hurts mainly a holder who has to sell, while a collateral loss is permanent.

Two qualifications apply. The short high-correlation regimes after Katrina, the 2011 Japanese earthquake and Sandy make *β*~ℓ~ small rather than exactly zero, and *π* is itself the price of catastrophe risk. What the decomposition separates is the occurrence of catastrophes, which markets do not drive, from the price and the packaging of catastrophe risk, which they can.

Equation (3) leads to three predictions.

1. In calm markets the collateral channel is closed and the premium moves little, so *β* is small. It need not be zero, since the link between CAT premiums and corporate spreads (Gürtler et al., 2016; Braun, 2016) exists outside crises, consistent with the post-2009 average correlation of about 0.10 (Drobetz et al., 2020).
2. The collateral channel can open only when the collateral is exposed to the credit of a financial institution: it could before 2009, and it is close to closed for deals whose collateral is held in Treasury funds or government-backed notes.
3. The premium channel opens when holders need cash as the market falls: they sell, and dealers short of capital buy only at a higher premium. Market and funding liquidity then reinforce each other (Brunnermeier and Pedersen, 2009), and slow-moving capital pushes prices below fundamentals before they recover (Duffie, 2010). If the capital available to bear catastrophe risk shrinks with financial wealth, its price also rises with credit spreads, which is what Gürtler et al. and Braun observe.

The zero-beta claim fails at its root when the peril is itself a macroeconomic shock (*β*~ℓ~ ≠ 0): pandemic bonds, and in my view systemic cyber bonds, belong to a different asset class.

## 3.3 Four stress regimes

Table 2 classifies stress episodes by whether the collateral was exposed to bank credit and whether investors needed cash (a funding crisis) or not (an equity sell-off).

**Table 2. Stress regimes implied by the decomposition, with the evidence for each**

| | Funding crisis (investors need cash) | Equity sell-off, no forced selling |
|:--|:--|:--|
| **Collateral exposed to bank credit (swap structures issued before 2009)** | Both channels open: beta turns positive. *Evidence:* correlation with stocks jumps after September 2008 (Carayannopoulos and Perez, 2015) and rises in extreme weeks before 2009 (Drobetz et al., 2020). | Only the insurance core is tested: beta close to zero. *Evidence:* correlation near zero in the first nine months of the recession (Carayannopoulos and Perez, 2015). |
| **Collateral in Treasury funds or government-backed notes (deals issued after 2009)** | Premium channel only: a small fall, later reversed; at most a weak safe haven. *Evidence:* safe haven after the COVID-19 outbreak (Feng and Zeng, 2025); fall of 0.81 percent in March 2020 (Insurance Insider ILS, 2020). | Neither channel open: beta close to zero, weak safe haven. *Evidence:* implied correlation of 0.01 to 0.05 in the worst post-2009 stock weeks (Drobetz et al., 2020); beta of 0.031 (Haffar and Le Fur, 2022). |

Source: classification by the author, based on the studies cited in each cell.

Each main result fits one cell. Since the grid was built after reading the evidence, this shows compatibility, not proof.

The top-left cell contains one episode, the months after Lehman's failure. The timing is consistent with the collateral channel but cannot isolate it: no forced selling of CAT bonds is documented in the first nine months of the recession, when the correlation stayed near zero. The positive pre-2009 extreme-week coefficients of Drobetz et al. belong here, since their pre-crisis period ends in December 2008, and the persistence of the regime until early 2011 fits swap-backed bonds that stayed outstanding and capital that returned slowly (Duffie, 2010).

The bottom-right cell explains the favourable results. As swap-backed deals matured after 2009 the collateral channel closed, and I assume, as the test of Section 3.5 can check, that post-crisis stock declines brought no forced selling on the scale of late 2008. The grid then predicts a beta close to zero and a weak safe haven, which is what the numbers show. The whole sample of Haffar and Le Fur lies in this cell, which is why their result is favourable and why it says nothing about funding crises.

March 2020 is the main test of the bottom-left cell: safe collateral combined with a severe scramble for cash. The framework predicts a fall driven by forced sales, no collateral loss, and a recovery. The Swiss Re price return index fell by 0.81 percent in the week to 20 March, with markdowns linked to bulk lists of bonds put up for sale (Insurance Insider ILS, 2020), and by May the sell-off was described as temporary (The Insurer, 2020). No natural catastrophe drove the fall and the collateral was safe, so in equation (1) *ℓ*~t~ = *k*~t~ = 0 and the fall equals *D*·Δ*π*~t~. With a spread duration of one to two years, the required premium rose by 0.81/*D*, about 40 to 80 basis points,[^duration] of the same order as the average liquidity premium of 98 basis points estimated by Herrmann and Hibbeln (2023). The premium channel thus opened but stayed small, consistent with Feng and Zeng still finding a safe haven. Their result fits the simple account too; what that account does not predict is a fall linked to forced sales and then reversed.

## 3.4 Measurement choices that move the answer

Part of the divergence is statistical. The first source is the gap between economic and statistical significance: CAT bond returns are much less volatile than stock returns, so a significant correlation can go with a tiny beta. In the data of Carayannopoulos and Perez, the crisis correlation of 0.25 goes with a beta that peaked at 0.014: a 20 percent fall in the S&P 500 would have cost a CAT bond investor about 0.3 percent.[^beta] The zero-beta claim is rejected statistically and close to true economically, and the articles differ partly in which of the two they stress.

The second is conditioning on volatility. Suppose the CAT bond return is *β* times the market return plus an independent shock with volatility *σ*~ε~. The correlation is then *ρ* = *β*·*σ*~m~/√(*β*²*σ*~m~² + *σ*~ε~²), which rises with the market's volatility *σ*~m~ whenever *β* > 0 (Forbes and Rigobon, 2002). In the data of Carayannopoulos and Perez, the weekly volatility of the S&P 500 rose from 1.91 to 4.49 percent, which at a constant beta and idiosyncratic volatility would lift the correlation only from 0.016 to under 0.04.[^fr] The rest of the rise to 0.252 is not mechanical, and their beta, which is free of this bias, also rose.

The third, smoothing, matters less than theory suggests. A smoothed index biases beta and correlation toward zero (Getmansky et al., 2004), but the results of Drobetz et al. and of Feng and Zeng hold with desmoothed returns. Smoothing also produces positive autocorrelation, while the index of Drobetz et al. has negative autocorrelation, which points instead to noise in quoted prices that reverses the following week, a problem desmoothing does not correct.

The fourth, the choice of proxy, measure and window, matters most. Before the crisis the correlation with stocks is 0.016 in Carayannopoulos and Perez but about 0.24 in Drobetz et al. The few weeks of late 2008 in the second sample cannot explain the gap,[^late2008] which must come from the series (a BB price index against a global total return index), the measure (a sample correlation against the mean of a DCC series) and the comparison index.

## 3.5 Proposed solutions

**Tests that could prove the framework wrong.**

- ***Split the 2008 beta between the two channels.*** Compare the Lehman-swap bonds with other CAT bonds from September to December 2008. A gap between the groups measures the collateral channel (plus any distress discount); a fall common to all bonds, larger at longer spread durations, measures the premium channel.
- ***Measure funding stress directly.*** Estimate DCC~t~ = *c*~0~ + *c*~1~·Ext~t~ + *c*~2~·Fund~t~ + *c*~3~·(Ext~t~ × Fund~t~), where Ext~t~ marks the worst 5 percent of stock weeks and Fund~t~ the top decile of funding stress, measured for example by the spread between commercial paper and Treasury bills. My framework predicts *c*~1~ close to zero and *c*~3~ > 0 in both periods, smaller after 2009; the simple account, in which 2008 was a special case, predicts *c*~3~ = 0 after 2009. March 2020 provides the main post-2009 observation.
- ***Separate catastrophe weeks.*** Weeks with a major catastrophe, such as Hurricane Ike in September 2008, need their own dummies, so that a catastrophe loss that coincides with a financial shock is not read as market beta.
- ***Re-run the favourable design on a funding crisis.*** The copula and co-kurtosis measures of Haffar and Le Fur, estimated on weekly data that include 2008 and March 2020, should show stronger extreme co-movement in funding-crisis weeks. Betas should be reported next to correlations, crisis correlations adjusted for volatility (Forbes and Rigobon, 2002), and TRACE prices used where possible (Herrmann and Hibbeln, 2023).

**Portfolio and market rules that remove what can be removed.**

- ***Keep the collateral channel closed.*** Investors should require collateral in Treasury money-market funds or government-backed notes, held in trust, marked to market and disclosed, and check each issue even though most of the market has moved this way since 2009 (Carayannopoulos and Perez, 2015).
- ***Contain the premium channel.*** Selling CAT bonds to raise cash in a crisis turns a temporary markdown into a realised loss. Funds that promise frequent redemptions should match them to the liquidity of their bonds through notice periods, cash buffers or redemption limits, and risk managers should stress allocations on a funding crisis such as March 2020.
- ***Limit concentration and classify perils honestly.*** Limits by peril, region and sponsor keep the insurance core diversified, and bonds on macroeconomic perils, such as pandemics, should not be modelled as zero-beta exposures.

## 3.6 Conclusion of the analysis

Whether CAT bonds are zero-beta assets depends on which part of the bond the question refers to. For natural perils the insurance core is zero-beta; the traded bond has a small beta in calm markets, one that can rise in a funding crisis, and one that rose, though it stayed economically small, in 2008. The safe-haven property depends on the structure of the asset and the type of stress, not only on the state of the market.

# 4. Conclusion

This paper asked to what extent CAT bonds retain their diversification benefits during financial stress, and why studies disagree. The decomposition of Section 3.2 explains the disagreement: the three main articles sample different cells of Table 2 with different proxies, frequencies and windows, so their conclusions can diverge while their estimates are compatible.

The answer to the research question is therefore conditional. CAT bonds kept their diversification benefit in every episode reviewed: even after Lehman's failure, their beta peaked at 0.014. Their safe-haven property holds, weakly, against stocks when the collateral is safe and holders are not forced to sell, and the framework predicts that it erodes when either condition fails. Investors should treat CAT bonds as a diversifier with a conditional safe-haven property, not as crisis insurance.

The analysis has limits. It rests on published results rather than new estimates, and the grid was built after reading the evidence, so the tests of Section 3.5 still need to be run. The bottom-left cell of Table 2 rests mainly on one episode, March 2020. Finally, the framework assumes that catastrophe losses are nearly independent of markets for natural perils, an assumption that holds only approximately and does not extend to pandemic or systemic cyber risks.

[^nested]: A week in the worst 5 percent of stock returns is also in the worst 10 percent but not in the worst 1 percent, so *d*~10%~ = *d*~5%~ = 1 and *d*~1%~ = 0, and the fitted correlation is *m*~0~ + *m*~1~ + *m*~2~ ≈ 0.10 + 0.04 − 0.09 = 0.05. Setting the insignificant *m*~1~ to zero gives 0.10 − 0.09 = 0.01. In the worst 1 percent of weeks all three dummies equal one: 0.10 + 0.04 − 0.09 + 0.10 = 0.15.

[^betasum]: Covariance is linear, Cov(*a* + *b*, *R*~m~) = Cov(*a*, *R*~m~) + Cov(*b*, *R*~m~), and dividing by Var(*R*~m~) gives the same rule for betas. *D* is treated as constant within a period, so the beta of *D*·Δ*π*~t~ is *D*·*β*~π~; the fixed spread *s* has a beta of zero.

[^duration]: The coupon is a floating money-market rate, which resets and barely moves the price, plus a fixed spread, which does not. If investors come to require Δ*π* more per year, the bond pays Δ*π* too little in each remaining year, so its price falls by about *D*·Δ*π*, with *D* close to the remaining life in years. An index holds bonds issued at different dates, so with maturities of three to four years at issue the average bond has about 1.5 to 2 years left; one to two years allows for bonds near maturity. A price return index also leaves out coupon income, so *r*~t~ and *s* drop out. Hence Δ*π* ≈ 0.81/2 ≈ 0.40 percent (40 basis points) for *D* = 2 and 0.81/1 = 0.81 percent (about 80 basis points) for *D* = 1.

[^beta]: By definition *β* = *ρ*·*σ*~CAT~/*σ*~m~. In the crisis sample *σ*~CAT~/*σ*~m~ = 0.41/4.49 ≈ 0.09, so a correlation of 0.25 implies a beta of about 0.25 × 0.09 ≈ 0.02, the same order as the dynamic peak of 0.014. With a beta of 0.014, a 20 percent fall in the S&P 500 moves the CAT bond by 0.014 × 20 = 0.28 percent.

[^fr]: Before the crisis, *ρ* = 0.016, *σ*~CAT~ = 0.37 and *σ*~m~ = 1.91 percent. Since *β* is tiny, practically all CAT bond volatility is idiosyncratic (*σ*~ε~ ≈ 0.37), and *β* ≈ 0.016 × 0.37/1.91 ≈ 0.003. Keeping *β* and *σ*~ε~ fixed and setting *σ*~m~ = 4.49 gives *ρ* ≈ (0.003 × 4.49)/√((0.003 × 4.49)² + 0.37²) ≈ 0.0139/0.370 ≈ 0.038.

[^late2008]: From mid-September to December 2008 is about 15 of the roughly 365 weekly observations of 2002-2008. Even if the correlation had been 1 in all 15 weeks and 0.016 in the other 350, its average would be (15 × 1 + 350 × 0.016)/365 ≈ 0.06, far below 0.24.

# Bibliography

Baur, Dirk G., and Brian M. Lucey (2010). "Is gold a hedge or a safe haven? An analysis of stocks, bonds and gold," *The Financial Review*, vol. 45, no. 2, pp. 217–229. https://doi.org/10.1111/j.1540-6288.2010.00244.x

Baur, Dirk G., and Thomas K. McDermott (2010). "Is gold a safe haven? International evidence," *Journal of Banking and Finance*, vol. 34, no. 8, pp. 1886–1898. https://doi.org/10.1016/j.jbankfin.2009.12.008

Braun, Alexander (2016). "Pricing in the primary market for cat bonds: New empirical evidence," *Journal of Risk and Insurance*, vol. 83, no. 4, pp. 811–847. https://doi.org/10.1111/jori.12067

Brunnermeier, Markus K., and Lasse Heje Pedersen (2009). "Market liquidity and funding liquidity," *Review of Financial Studies*, vol. 22, no. 6, pp. 2201–2238. https://doi.org/10.1093/rfs/hhn098

Carayannopoulos, Peter, and M. Fabricio Perez (2015). "Diversification through catastrophe bonds: Lessons from the subprime financial crisis," *The Geneva Papers on Risk and Insurance – Issues and Practice*, vol. 40, no. 1, pp. 1–28. https://doi.org/10.1057/gpp.2014.14

Cummins, J. David (2008). "CAT bonds and other risk-linked securities: State of the market and recent developments," *Risk Management and Insurance Review*, vol. 11, no. 1, pp. 23–47. https://doi.org/10.1111/j.1540-6296.2008.00127.x

Drobetz, Wolfgang, Henning Schröder, and Lars Tegtmeier (2020). "The role of catastrophe bonds in an international multi-asset portfolio: Diversifier, hedge, or safe haven?" *Finance Research Letters*, vol. 33, article 101198. https://doi.org/10.1016/j.frl.2019.05.016

Duffie, Darrell (2010). "Presidential address: Asset price dynamics with slow-moving capital," *Journal of Finance*, vol. 65, no. 4, pp. 1237–1267. https://doi.org/10.1111/j.1540-6261.2010.01569.x

Feng, Chi, and Xudong Zeng (2025). "The Covid-19 pandemic and the portfolio diversification effect of catastrophe bonds," *Journal of Risk*, vol. 27, no. 4. https://doi.org/10.21314/JOR.2024.022

Forbes, Kristin J., and Roberto Rigobon (2002). "No contagion, only interdependence: Measuring stock market comovements," *Journal of Finance*, vol. 57, no. 5, pp. 2223–2261. https://doi.org/10.1111/0022-1082.00494

Getmansky, Mila, Andrew W. Lo, and Igor Makarov (2004). "An econometric model of serial correlation and illiquidity in hedge fund returns," *Journal of Financial Economics*, vol. 74, no. 3, pp. 529–609. https://doi.org/10.1016/j.jfineco.2004.04.001

Gürtler, Marc, Martin Hibbeln, and Christine Winkelvos (2016). "The impact of the financial crisis and natural catastrophes on CAT bonds," *Journal of Risk and Insurance*, vol. 83, no. 3, pp. 579–612. https://doi.org/10.1111/jori.12057

Haffar, Adlane, and Éric Le Fur (2022). "Dependence structure of CAT bonds and portfolio diversification: A copula-GARCH approach," *Journal of Asset Management*, vol. 23, no. 4, pp. 297–309. https://doi.org/10.1057/s41260-022-00271-3

Herrmann, Markus, and Martin Hibbeln (2023). "Trading and liquidity in the catastrophe bond market," *Journal of Risk and Insurance*, vol. 90, no. 2, pp. 283–328. https://doi.org/10.1111/jori.12407

Insurance Insider ILS (2020). "Cat bond prices limit Covid-19 fall to under 1%," *Insurance Insider ILS*, March 2020. https://www.insuranceinsiderils.com/article/2876fhy9ajjsuvp26rkuq/cat-bond-prices-limit-covid-19-fall-to-under-1

The Insurer (2020). "Cat bonds nudge up after temporary Covid-19 sell-off," *The Insurer*, May 2020. https://theinsurer.com/analysis/cat-bonds-nudge-up-after-temporary-covid-19-sell-off
