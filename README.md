# isye6420---homework-4-solved
**TO GET THIS SOLUTION VISIT:** [ISYE6420 – Homework 4 Solved](https://www.ankitcodinghub.com/product/isye6420-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;105116&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISYE6420 - Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
ISyE 6420

Use of unsolicited electronic and printed resources is allowed except the communication that violates Georgia Tech Academic Integrity Rules (e.g., direct communication about solutions with a third party, use of HW-solving sites, and similar).

1. Metropolis for Correlation Coefficient. Pairs (Xi,Yi),i = 1,…,n consist of correlated standard normal random variables (mean 0, variance 1) forming a sample from a bivariate normal MVN2(0,Σ) distribution, with covariance matrix

.

The density of (X,Y ) ∼ MVN2(0,Σ) is

,

with ρ as the only parameter. Take prior on ρ by assuming Jeffreys’ prior on Σ as π(Σ) = , since the determinant of Σ is 1 − ρ2. Thus

.

(a) If (Xi,Yi),i = 1,…,n are observed, write down the likelihood for ρ. Write down the expression for the posterior, up to the proportionality constant (that is, un-normalized posterior as the product of likelihood and prior).

(b) Since the posterior for ρ is complicated, develop a Metropolis-Hastings algorithm to sample from the posterior. Assume that n = 100 observed pairs (Xi,Yi) gave the following summaries:

, and .

In forming a Metropolis-Hastings chain take the following proposal distribution for ρ: At step i generate a candidate ρ0 from the uniform U(ρi−1 − 0.1,ρi−1 + 0.1) distribution. Why the proposal distribution cancels in the acceptance ratio expression?

(c) Simulate 51000 samples from the posterior of ρ and discard the first 1000 samples (burn in). Plot two figures: the histogram of ρs and the realizations of the chain for the last 1000 simulations. What is the Bayes estimator of ρ based on the simulated chain?

(d) Replace the proposal distribution from (b) by the uniform U(−1,1) (independence proposal). Comment on the results of MCMC.

2. Gibbs Sampler and Lifetimes with Multiplicative Frailty. Exponentially distributed lifetimes have constant hazard rate equal to the rate parameter λ. When λ is a constant hazard rate, a simple way to model heterogeneity of hazards is to introduce a multiplicative frailty parameter µ, so that lifetimes Ti have distribution

Ti ∼ f(ti|λ,µ) = λµexp{−λµti}, ti &gt; 0, λ,µ &gt; 0.

The prior on (λ,µ) is

π(λ,µ) ∝ λc−1µd−1 exp{−αλ − βµ},

that is, λ and µ are apriori independent with distributions Ga(c,α) and Ga(d,β), respectively.

The hyperparameters c,d,α and β are known (elicited) and positive.

Assume that lifetimes t1,t2,…,tn are observed.

(a) Show that full conditionals for λ and µ are gamma,

,

and by symmetry,

.

(b) Using the result from (a) develop Gibbs Sampler algorithm that will sample 51000 pairs (λ,µ) from the posterior and burn-in the first 1000 simulations. Assume that n = 20 and that the sum of observed lifetimes is .

Assume further that the priors are specified by hyperparameters c = 3,d = 1,α = 100, and β = 5. Start the chain with µ = 0.1.

(c) From the produced chain, plot the scatterplot of (λ,µ) as well as histograms of individual components, λ, and µ. Estimate posterior means and variances for λ and µ. Find 95% equitailed credible sets for λ and µ.

(d) A frequentist statistician estimates the product .

What is the Bayes estimator of this product? (Hint: It is not the product of averages, it is the average of products, so you will need to save products in the MCMC loop).

2
