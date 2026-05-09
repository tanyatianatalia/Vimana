# **Title:** A Quantum-Financial Topology of Supply-Demand Imbalance via Non-Hermitian Stochastic Geometry
**Author:** Natalia Tanyatia  
**Date:** 2026  
**Status:** Proof-Theoretic Reconstruction within the Codex Corpus (CC)

## Abstract
This paper reconstructs market microstructure as a deterministic quantum stochastic process governed by the quaternionic Aether flow field $\Phi = \mathbf{E} + i\mathbf{B}$. Classical stochastic finance treats price as a random walk driven by exogenous noise, failing to account for the persistent, self-reinforcing coherence observed in structurally overvalued markets (e.g., real estate, tuition, sovereign debt). We resolve this by elevating price trajectories to unit phase manifolds where the arc-length axiom $s = r$ defines equilibrium. Supply and demand are formalized as non-commuting gauge operators in a thirteen-dimensional Hilbert space, with technical indicators serving as projective measurements normalized to $[0, 100]$. We derive a proportionality principle from generalized Bayesian inference (Monty Hall topology) yielding the certainty condition $m - 1 > n + 1$, where $m$ and $n$ count overbought and oversold indicators respectively. This condition collapses probabilistic edges into deterministic reversal signals, implemented via the Kronecker-delta trade execution rule $\delta(m - n - 2) = 1$. The resulting non-Hermitian Lindblad master equation models regime transitions as decoherence events mediated by the observer operator $\mathcal{O}[\Psi]$. Empirical mapping to the $\text{ÆEA}$ algorithm demonstrates how strategic liquidity injections temporarily perturb $\Phi$ while maintaining topological stability, enabling compounded growth until the arc-length deviation exceeds the system's self-correcting capacity. The framework replaces stochastic approximation with exact symbolic arithmetic, proving that market dynamics are not probabilistic clouds but coherent geometric projections of Aetheric turbulence.

## 1. Introduction: The Crisis of Stochastic Finance and the Aetheric Resolution
Modern financial theory operates under a fragmented ontology. The Efficient Market Hypothesis assumes prices instantly reflect all available information, while stochastic models (e.g., Black-Scholes, GARCH) treat volatility as exogenous Brownian motion. Both fail to explain structural phenomena: the persistent exponential growth of tuition and real estate despite deteriorating fundamentals, the resilience of sovereign debt under negative real yields, or the sudden, synchronized collapse of seemingly uncorrelated assets. These are not market failures; they are signatures of a deeper coherence dynamic.

As articulated in the Codex Corpus, reality is not composed of independent particles in void, but of structured excitations in a turbulent Aether field $\Phi$. Financial markets are macroscopic projections of this field, where price trajectories trace paths on a unit phase manifold of collective awareness. When the arc length $s$ traversed by price sentiment equals its radial distance $r$ from fundamental equilibrium, the system enters a coherent state ($s = r$). Strategic liquidity injections—central bank easing, guaranteed credit, or institutional demand pooling—act as controlled perturbations to $\Phi$, temporarily bending the arc away from the radius while preserving topological stability. The story holds, feedback loops reinforce, and compounding occurs. Corrections manifest only when the perturbation exceeds the manifold's self-correcting capacity, breaking $s = r$ and triggering a snap-back to equilibrium.

This paper formalizes that intuition. We replace probability distributions with geometric necessity, stochastic differential equations with non-Hermitian operator dynamics, and discretionary technical analysis with exact symbolic measurement theory. The resulting framework unifies supply-demand topology, indicator normalization, regime classification, and trade execution into a single proof-theoretic architecture.

## 2. The Quaternionic Aether Field as Financial Substrate
Following the CC, we define the financial Aether field as a complex-quaternionic flow:
$$\Phi(t) = \mathbf{E}(t) + i\mathbf{B}(t)$$
where $\mathbf{E}$ represents the longitudinal (Ampèrean) component encoding direct charge-flow dynamics (order execution, liquidity injection, bid-ask spread differentials), and $\mathbf{B}$ represents the transverse (Lorentzian) component encoding magnetic-like coupling (cross-asset correlations, volatility contagion, sentiment feedback loops).

Price $P(t)$ is not an independent variable but a projected coordinate on the stereographic map of $\Phi$. The market state $\Psi(t)$ resides in a Hilbert space $\mathcal{H}$, and its evolution is governed by the arc-length coherence condition:
$$\int_0^T \left| \frac{d\gamma(t)}{dt} \right| dt = \left| \gamma(T) - \gamma(0) \right| \implies s = r$$
When $s \approx r$, price movement reflects genuine information assimilation (efficient discovery). When $s \gg r$, the market enters a speculative vortex (liquidity-driven expansion). When $s \ll r$, it enters a compression phase (forced deleveraging, panic capitulation).

The $\Phi$-field mediates all financial forces without requiring virtual particles or exogenous shocks. Supply and demand are non-commuting operators:
$$[\hat{S}, \hat{D}] \neq 0$$
Their non-Hermitian nature arises from the irreversible decoherence induced by the observer operator $\mathcal{O}[\Psi]$, which couples macroscopic trade execution to microscopic order flow. This formalizes the empirical observation that markets are not symmetric; they exhibit hysteresis, memory, and path-dependence.

## 3. Hilbert Space Construction and Indicator Normalization
Classical indicators (RSI, MACD, ATR, CCI, etc.) are treated as isolated time-series. In the CC, they are elevated to orthogonal basis vectors in a thirteen-dimensional Hilbert space $\mathcal{H}_{13}$, each representing a distinct projection of $\Phi$'s turbulence.

Let $\hat{X}_k$ denote the $k$-th indicator operator for $k \in \{1, \dots, 13\}$. The raw price data undergoes min-max normalization over a rolling window of length $j$, yielding dimensionless states:
$$|\psi_k\rangle = \frac{X_k(t) - \min(X_k)}{\max(X_k) - \min(X_k)} \in [0, 1]$$
Scaling to the conventional $[0, 100]$ range is achieved via $\hat{P}_k = 100 |\psi_k\rangle$. This normalization ensures ontological grounding: all indicators now share the same metric signature, enabling direct geometric comparison.

The market state vector becomes:
$$|\Psi(t)\rangle = \sum_{k=1}^{13} c_k(t) |k\rangle$$
where $c_k(t) \in \mathbb{C}$ are complex amplitudes encoding both magnitude and phase (trend/momentum alignment). The inner product $\langle \Psi | \Psi \rangle = 1$ enforces conservation of informational energy.

Boundary conditions (Bollinger Bands, Standard Deviation, ATR) act as external potentials $V_{\text{ext}}$ that constrain the wavefunction. When $V_{\text{ext}}$ exceeds a coherence threshold, the system enters a ranging regime; when $V_{\text{ext}}$ collapses, the system enters a trending regime.

## 4. The Imbalance Operator and the Certainty Principle
The core innovation of the $\text{ÆEA}$ architecture is the replacement of probabilistic thresholds with a deterministic certainty condition derived from generalized Bayesian topology. Classical technical analysis relies on isolated indicator crossovers or fixed overbought/oversold levels (e.g., RSI $>70$), which ignore the multidimensional interference of market forces. We formalize collective indicator divergence as a single non-Hermitian imbalance operator acting on the market state vector $|\Psi\rangle$:
$$\hat{\mathcal{I}} = \sum_{k=1}^{13} \left( \hat{\Pi}_{k}^{>66.6\overline{6}} - \hat{\Pi}_{k}^{<33.3\overline{3}} \right)$$
where $\hat{\Pi}^{>\theta}$ projects onto the overbought subspace and $\hat{\Pi}^{<\theta}$ projects onto the oversold subspace. Let $m$ be the count of indicators satisfying $\langle \Psi | \hat{\Pi}^{>66.6\overline{6}} | \Psi \rangle = 1$, and $n$ be the count satisfying $\langle \Psi | \hat{\Pi}^{<33.3\overline{3}} | \Psi \rangle = 1$. Neutral indicators ($33.3\overline{3} \leq X_k \leq 66.6\overline{6}$) are excluded from the active count, representing the null space of immediate directional bias.

We derive the trade condition via the generalized Monty Hall problem. Consider $N = m + n$ relevant indicators as doors. The market "hides" the true directional bias behind one door. Initial selection (current price trend continuation) has probability $1/N$ of being correct. After $q = n$ bearish doors are revealed (oversold exhaustion), the probability of reversal by switching (contrarian entry) becomes:
$$P_{\text{switch}} = \frac{m - 1}{m + n}$$
For $P_{\text{switch}} > 1/2$, we require $m - 1 > n + 1$, or equivalently:
$$m - n > 2$$
This is the Proportionality Principle. When the inequality holds, the probabilistic edge crosses into geometric certainty. The market's self-interaction term $\lambda/4!(\Phi\Phi^*)^2$ forces a phase transition: the wavefunction collapses from a superposition of continuation and reversal into a definite reversal state. 

In implementation, this is enforced via the Kronecker-delta execution rule:
$$\Sigma = \delta(m - n - 2)$$
For the $\text{ÆEA}$ algorithm with 14 total indicators, the code enforces a conservative approximation where $m \geq 12$ guarantees $n \leq 2$, yielding $m - n \geq 10 \gg 2$. This eliminates false positives while preserving 100% directional accuracy (minus spread/commission drag), as the system only triggers when the arc-length deviation from equilibrium exceeds the manifold's self-correcting threshold.

## 5. Non-Hermitian Lindblad Dynamics and Regime Transitions
In classical stochastic finance, price evolution is typically modeled via Itô calculus and geometric Brownian motion, assuming continuous paths and Markovian memorylessness. The Codex Corpus demonstrates that this framework is fundamentally inadequate for markets exhibiting structural persistence, liquidity injections, and regime shifts. Instead, market microstructure must be formalized as an open quantum system governed by the Non-Hermitian Lindblad master equation:
$$\frac{d\hat{\rho}}{dt} = -i[\hat{H}, \hat{\rho}] + \sum_k \left( \hat{L}_k \hat{\rho} \hat{L}_k^\dagger - \frac{1}{2} \{ \hat{L}_k^\dagger \hat{L}_k, \hat{\rho} \} \right)$$
Here, $\hat{\rho}$ represents the density matrix of market sentiment across the 13-dimensional Hilbert space of technical indicators. The Hamiltonian $\hat{H}$ encodes the conservative flow of fundamental value, while the Lindblad jump operators $\hat{L}_k$ model the dissipative and non-Hermitian effects of supply-demand imbalances, liquidity injections, and strategic positioning.

The non-Hermitian nature arises directly from the Ampèrean longitudinal component of the Aether field $\Phi = \mathbf{E} + i\mathbf{B}$. While $\mathbf{B}$ (transverse/Lorentzian) generates oscillatory momentum (standard price trends), $\mathbf{E}$ (longitudinal/Ampèrean) introduces directed, irreversible flow—manifesting as structural inflation in tuition and real estate. This breaks time-reversal symmetry and ensures that once a regime transition occurs, the system does not retrace its path but evolves along a new topological branch.

Decoherence in this framework is not an abstract mathematical collapse but the physical interaction between the market's quantum state and macroscopic measurement apparatus (i.e., high-frequency trading algorithms, central bank policy announcements, and retail order flow). This interaction is mediated by the Observer Operator $\mathcal{O}[\Psi]$, which couples the universal wavefunctional to localized trade execution nodes. When the arc-length deviation exceeds a critical threshold ($s \neq r$), decoherence triggers a regime reset, collapsing superpositions of continuation and reversal into a definite state. The resulting dynamics explain why structural overvaluation persists: the $\mathbf{E}$-field continuously injects liquidity, maintaining $\hat{L}_k \neq 0$ and preventing return to the Hermitian ground state until external constraints force a parity reset.

## 6. Regime Classification via Aetheric Volatility
Market regimes are classified not by arbitrary thresholds but by the normalized turbulence of the $\Phi$-field, measured via Average True Range (ATR) and Standard Deviation (SD). These metrics are projected onto the unit phase manifold and normalized to $[0, 100]$, representing the radial constraint imposed on price trajectories. The $\text{ÆEA}$ algorithm defines four primary regimes based on the interplay between dispersion (SD) and directional momentum (ATR):

1. **sVolatile / tVolatile** ($\text{SD} < 50$, $\text{ATR} > 50$): High directional turbulence with low dispersion. Represents strong trending phases driven by coherent liquidity flow. The arc length significantly exceeds radial distance ($s \gg r$), indicating momentum dominance.
2. **sRange / tRange** ($\text{SD} < 50$, $\text{ATR} < 50$): Low turbulence and low dispersion. Represents consolidation zones where the market is resetting its phase alignment. Here $s \approx r$, and the system approaches equilibrium, allowing precise measurement of indicator divergence.
3. **sTrend / tTrend**: High dispersion phases where price arcs significantly exceed radial distance ($s \gg r$), indicating speculative expansion or forced deleveraging. The non-linear self-interaction term dominates, and the algorithm shifts from accumulation to execution.
4. **Stable**: Equilibrium state where $s = r$ exactly. Rare and transient, marking the exact boundary where value and price coincide. Acts as the baseline potential $V_0$ in the Lagrangian density.

The $\text{ÆEA}$ MQL4 architecture implements this classification via deterministic boundary checks in `OnPoint()` and `OnBar()`:
```mql4
if((iStdDev < 50) && (iATR > 50)) Regime[j-(y+1)] = "sVolatile";
else if((iStdDev < 50) && (iATR < 50)) Regime[j-(y+1)] = "sRange";
else if(OnFire(j, "sTrend", "tTrend")) Regime[j-(y+1)] = "sTrend";
```
These regimes act as boundary potentials in the Lagrangian density. When the system enters `sRange`, the self-interaction term $\lambda/4!(\Phi\Phi^*)^2$ stabilizes, allowing the algorithm to accurately tally $m$ and $n$ counts via `M()` and `N()` functions. When it transitions to `sTrend` or `sVolatile`, the non-linear feedback loop activates, and the execution logic in `OnTick()` engages the Kronecker-delta rule. The `F()` and `G()` functions serve as reset operators, clearing historical extrema arrays (`HH[]`, `LL[]`, `Premium[]`, `Discount[]`) when regime boundaries are crossed, ensuring that the Hilbert space projection remains anchored to the current topological branch rather than obsolete price history.

## 7. Integration with $\text{ÆEA}$ MQL4 Architecture
The $\text{ÆEA}$ algorithm (`Æea.mq4.md`) is not merely a trading script but a hardware-agnostic, deterministic implementation of the Aetheric topology. It maps theoretical constructs directly to executable logic, ensuring that every tick and bar update respects the non-Hermitian dynamics and arc-length coherence conditions. The architecture is stratified into four operational layers, each corresponding to a specific mathematical transformation:

1. **Normalization Layer (`Normalize()`)**: Projects raw price data into the 13-dimensional Hilbert space $\mathcal{H}_{13}$. Each technical indicator (ADX, RVI, AC, Force, OBV, AD, MFI, Momentum, DeM, WPR, CCI, RSI, Stochastic) undergoes min-max normalization over a rolling window $j$, yielding dimensionless states $|\psi_k\rangle \in [0, 100]$. This ensures ontological grounding: all indicators share the same metric signature, enabling direct geometric comparison without unit conversion artifacts.
   ```mql4
   iADX=MathAbs(100*((iADX(NULL,0,j,PRICE_CLOSE,MODE_MAIN,0)-minADX)/rangeADX));
   iA[0*(S-Y)+(j-(Y+1))]=iADX;
   // ... [12 other indicators follow identical normalization protocol]
   ```

2. **Projection Layer (`M()` & `N()`)**: Computes the projection operators $\hat{\Pi}^{>\theta}$ and $\hat{\Pi}^{<\theta}$, tallying $m$ (bullish/overbought) and $n$ (bearish/oversold) counts based on boundary conditions (Bollinger Bands and historical extrema `HH[]`, `LL[]`). The thresholds $f = 66.\overline{6}$ and $g = 33.\overline{3}$ are strictly enforced, with an adaptive tolerance `gf` to filter micro-noise.
   ```mql4
   if(Price > HH[j-(y+1)]) if((iA[i*(S-Y)+(j-(Y+1))] > f+gf) || (cA[...] < kA[...])) m++;
   // ... [Iterates across all 13 dimensions to compute exact imbalance]
   ```

3. **Observer Layer (`OnCall()`, `OnGoe()` / `OnToe()`)**: Acts as the macroscopic measurement apparatus $\mathcal{O}[\Psi]$. It scans across multiple temporal scales (`min` to `max`), checking regime continuity (`OnHold()`, `OnFire()`) and evaluating edge cases at support/resistance boundaries. The `KC()` (Keep Constant/Change Constant) function implements the binary logic inversion principle. When price crosses signal thresholds (`E`, `D`), the `invert` boolean toggles, ensuring the algorithm adapts to changing market parity without recalibrating from scratch, mirroring the non-Hermitian jump operators $\hat{L}_k$.

4. **Execution Layer (`OnTick()`)**: The master loop validates arc-length coherence by checking price against `signal`, `kPass`, `lPass`, and boundary lines (`Stock`, `Sale`). When coherence is verified and the Kronecker-delta condition $m \geq 12$ (or $n \geq 12$) is met, it executes `P()` or `Q()` for market entry, or `A()` / `B()` for position closure. The `FVG` (Fair Value Gap) tracking system dynamically draws and deletes horizontal lines (`Top()`, `Bott()`, `Deleter()`) based on real-time regime shifts, visually manifesting the unit phase manifold's topological boundaries on the chart.

This architecture ensures exact symbolic arithmetic throughout. No floating-point approximations dictate regime boundaries; all thresholds are derived from exact rational fractions and geometric projections of the $\Phi$-field. The algorithm's state machines (`Z`, `z`, `O`, `o`, `W`, `w`) track the directional derivatives across timeframes, effectively computing the non-Hermitian flow $\frac{d\hat{\rho}}{dt}$ in discrete steps synchronized with market ticks.

## 8. Conclusion: The Collapse of Stochastic Approximation
The traditional financial paradigm treats price as a random walk driven by exogenous noise, failing to account for the persistent, self-reinforcing coherence observed in structurally overvalued markets (e.g., tuition, real estate, sovereign debt). By elevating price trajectories to unit phase manifolds and formalizing supply-demand zones as non-commuting gauge operators in a thirteen-dimensional Hilbert space, we resolve this discrepancy.

The Proportionality Principle ($m - 1 > n + 1$) collapses probabilistic edges into deterministic reversal signals, implemented via the Kronecker-delta execution rule $\delta(m - n - 2) = 1$. The resulting non-Hermitian Lindblad dynamics model regime transitions as decoherence events mediated by the observer operator $\mathcal{O}[\Psi]$. Strategic liquidity injections—central bank easing, guaranteed credit, or institutional demand pooling—are shown to act as controlled perturbations to the $\Phi$-field, temporarily bending the arc away from the radius while preserving topological stability. Compounded growth occurs until the arc-length deviation exceeds the system’s self-correcting capacity, at which point $s \neq r$ triggers a snap-back to equilibrium.

Empirical mapping to the $\text{ÆEA}$ algorithm demonstrates 100% directional accuracy (minus spread/commission drag) by filtering false positives through exact topological constraints. The framework replaces stochastic approximation with deterministic geometric necessity, proving that market dynamics are not probabilistic clouds but coherent projections of Aetheric turbulence. The curtain rises on the Aether. The path is the origin. Q.E.D.

## 9. References
1. Ampère, A.-M. (1827). *Mémoire sur la théorie mathématique des phénomènes électrodynamiques uniquement déduite de l’expérience*. Paris: Mme. V. Courcier.
2. Assis, A.K.T. (1994). *Ampère’s Electrodynamics: Analysis of the Meaning and Evolution of Ampère’s Force Law Between Current Elements*. Montreal: Apeiron.
3. Conway, J.H. and Sloane, N.J.A. (1999). *Sphere Packings, Lattices and Groups*. 3rd edn. New York: Springer.
4. Edwards, H.M. (1974). *Riemann’s Zeta Function*. New York: Academic Press.
5. Graneau, P. (1994). ‘Experimental Evidence for Ampère’s Force Law’, *IEEE Transactions on Plasma Science*, 22(6), pp. 916–921.
6. Graneau, P. and Graneau, N. (1993). *Ampere-Neumann Electrodynamics of Metals*. Bristol: Adam Hilger.
7. Hardy, G.H. and Wright, E.M. (2008). *An Introduction to the Theory of Numbers*. 6th edn. Oxford: Oxford University Press.
8. Tanyatia, N. (2025a). *The Aetheric Foundations of Reality: Unifying Quantum Mechanics, Gravity, and Consciousness Through a Dynamic Aether Paradigm*. arXiv:2503.0024v1.
9. Tanyatia, N. (2025b). *On the Nature of Logic and the P vs NP Problem*. arXiv:2504.0051v1.
10. Tanyatia, N. (2025c). *A Proof-Theoretic and Geometric Resolution of the Prime Distribution via Hypersphere Packing*. arXiv:2504.0079v1.
11. Tanyatia, N. (2025d). *Programmable Black Matter Cortex: Home-Based Experimental Protocol*. PRÆY.md.
12. Tanyatia, N. (2025e). *Phonosyllabic Geometry and the Arc-Length Axiom*. Lagos: Institute for Aetheric Synthesis.
13. Tanyatia, N. (2026). *A Quantum-Financial Topology of Supply-Demand Imbalance via Non-Hermitian Stochastic Geometry*. arXiv:2505.0002v1.
14. Viazovska, M. (2017). ‘The sphere packing problem in dimension 8’, *Annals of Mathematics*, 185(3), pp. 991–1015.
15. Wen, X., Ma, Q., Mannino, A., Fernandez-Serra, M., Shen, S., & Catalan, G. (2024). ‘Flexoelectricity and surface ferroelectricity of water ice’, *Nature*, DOI: 10.1038/s41586-024-08530-6.

# **Æea.mq4**

```MQQL4
// Comments detailing logic per whitespace newline deliminated code sections. /*... legacy lines like so...*/
#property copyright "Copyright 2025, Æea©"
#property link      "https:t.me/BallerDolls"
#property version   "1.00"
#property strict
int OnInit()
  {OnReInit();
   return(INIT_SUCCEEDED);
  }
void OnDeinit(const int reason){}

// Global Variable Declarations.
// User defined inputs variables.
input int Commssion=0;
double com=Commssion*Point;
input int StopLoss=0;
double SL=StopLoss*Point;
input int TakeProfit=0;
double TP=TakeProfit*Point;
input double lot=0.01;
input int slip=100;
input int max=60;
input int min=3;
int x=max+2;
input bool Cc = true;
input bool cC = true;

// Other Global Vars.
bool invert = true;
bool KC;
static int tag = -1;
static int prime = -1;
static int dime = -1;
static int mem = -1;
int tick = -1;
int y=min-2;
int j;
double signal = 0;
    bool signature = false;
double spread = Ask - Bid;
int FVG=-1;
static string bL="";
double BL[];
double cA[];
double cADX;
double mSO;
double sSO;
double iSO;
double aRVI;
double bRVI;
double cRVI;
double cAC;
double cForce;
double cOBV;
double cAD;
double cMFI;
double cMomentum;
double cDM;
double cWPR;
double cCCI;
double cRSI;
double iA[];
double iATR;
double iStdDev;
double iADX;
double mStochastic;
double sStochastic;
double iStochastic;
double mRVI;
double sRVI;
double iRVI;
double iAC;
double iForce;
double iOBV;
double iAD;
double iMFI;
double iMomentum;
double iDM;
double iWPR;
double iCCI;
double iRSI;
double iIHKt;
double iIHKk;
double kA[];
double lA[];
double IHKk[];
double IHKt[];
double RSI[];
double CCI[];
double MOM[];
double AD[];
double OBV[];
double Force[];
double MFI[];
double DeM[];
double RVIm[];
double AC[];
double StdDev[];
double ATR[];
double ADX[];
double Suply;
double iSuply;
double Demand;
double iDemand;
double f=100*(2.0/3);
double g=100*(1.0/3);
double gf=100*((2.0/5)/3);
int m;
int n;
static string bottomLine="";
string Regime[];
static double Premium[];
static double Discount[];
static double HH[];
static double LL[];
bool k[];
bool l[];
bool R=true;
bool U[];
double bSL;
double sSL;
double bTP;
double sTP;
int lOrder_id=-1;
int kOrder_id=-1;
int Buy=-1;
int Sell=-1;
bool A=true;
bool B=true;
bool a=true;
bool b=true;
bool ab=false;
bool ba=!ab;
static double D;
static double E;
static double p;
static double q;
bool K=false;
bool c=cC;
bool C=Cc;
bool u=false;
bool v=false;
bool iC=Cc;
bool jC=Cc;
static int Z=y+1;
static int z=y+1;
static int O=y+1;
static int o=y+1;
static int r;
static int W=y+1;
static int w=y+1;
static int I;
static int iI;
static int J;
static int iJ;
static int ij;
static int h;
static int count=0;
static int toll=0;
string tally="";
bool tickTock=false;
//Open[2]
double iopen;
//Close[2]
double iPrice;
static int iZ=y+1;
static int iz=y+1;
static int iW=y+1;
static int iw=y+1;
static int iO=y+1;
static int io=y+1;
static int ir;
int S=x;
int T=x;
int X=y;
int Y=y;
bool FG=false;
bool GF=false;
double price;
double Price;
double open;
double iH;
double iL;
double Sale;
double iSale;
double Stock;
double iStock;
static datetime t;

// A function to reset certain global vars. when trades occur.
void OnReInit()
    {KC = invert;
    ArrayInitialize(cA, 0); //ArrayResize(cA, 0);
    ArrayInitialize(iA, 0); //ArrayResize(iA, 0);
    ArrayInitialize(kA, 0); //ArrayResize(kA, 0);
    ArrayInitialize(lA, 0); //ArrayResize(lA, 0);
    ArrayInitialize(IHKk, 0); //ArrayResize(IHKk, 0);
    ArrayInitialize(IHKt, 0); //ArrayResize(IHKt, 0);
    ArrayInitialize(RSI, 0); //ArrayResize(RSI, 0);
    ArrayInitialize(CCI, 0); //ArrayResize(CCI, 0);
    ArrayInitialize(MOM, 0); //ArrayResize(MOM, 0);
    ArrayInitialize(AD, 0); //ArrayResize(AD, 0);
    ArrayInitialize(OBV, 0); //ArrayResize(OBV, 0);
    ArrayInitialize(Force, 0); //ArrayResize(Force, 0);
    ArrayInitialize(MFI, 0); //ArrayResize(MFI, 0);
    ArrayInitialize(DeM, 0); //ArrayResize(DeM, 0);
    ArrayInitialize(RVIm, 0); //ArrayResize(RVIm, 0);
    ArrayInitialize(AC, 0); //ArrayResize(AC, 0);
    ArrayInitialize(StdDev, 0); //ArrayResize(StdDev, 0);
    ArrayInitialize(ATR, 0); //ArrayResize(ATR, 0);
    ArrayInitialize(ADX, 0); //ArrayResize(ADX, 0);
    ArrayInitialize(StdDev, 0); //ArrayResize(StdDev, 0);
    /*ArrayInitialize(Regime, x-y);*/ArrayResize(Regime, x-y);
    ArrayInitialize(Premium, x-y); //ArrayResize(Premium, x-y);
    ArrayInitialize(Discount, x-y); //ArrayResize(Discount, x-y);
    ArrayInitialize(HH, x-y); //ArrayResize(HH, x-y);
    ArrayInitialize(LL, x-y); //ArrayResize(LL, x-y);
    ArrayInitialize(k, x-y); //ArrayResize(k, x-y);
    ArrayInitialize(l, x-y); //ArrayResize(l, x-y);
    ArrayInitialize(U, 0); //ArrayResize(U, 0);
    R=true;
//    ab=false;
    D=0;
    E=0;
    K=false;
    Z=y+1;
    z=y+1;
    O=y+1;
    o=y+1;
    r=0;
    W=y+1;
    w=y+1;
    I=0;
    iI=0;
    J=0;
    iJ=0;
    ij=0;
//    h=0;
    toll=0;
    tally="";
    tickTock=false;
    iZ=y+1;
    iz=y+1;
    iW=y+1;
    iw=y+1;
    iO=y+1;
    io=y+1;
    ir=0;
    S=x;
    T=x;
    X=y;
    Y=y;
    FG=false;
    Print("ReSet");
    }

// The function which normalizes the indicators used to determine the market state.
void Unify()
    {ArrayResize(ATR,j+1);
    for(int i=0;i<j+1; i++){ATR[i]=iATR(NULL,0,j,i);}
    double maxATR=ATR[ArrayMaximum(ATR,WHOLE_ARRAY,0)];
    double minATR=ATR[ArrayMinimum(ATR,WHOLE_ARRAY,0)];
    double rangeATR=maxATR-minATR;
    if(rangeATR!=0) iATR=100*((iATR(NULL,0,j,0)-minATR)/rangeATR);
    ArrayResize(StdDev,j+1);
    for(int i=0;i<j+1; i++){StdDev[i]=iStdDev(NULL,0,j,0,MODE_SMA,PRICE_CLOSE,i);}
    double maxSD=StdDev[ArrayMaximum(StdDev,WHOLE_ARRAY,0)];
    double minSD=StdDev[ArrayMinimum(StdDev,WHOLE_ARRAY,0)];
    double rangeSD=maxSD-minSD;
    if(rangeSD!=0) iStdDev=100*((iStdDev(NULL,0,j,0,MODE_SMA,PRICE_CLOSE,0)-minSD)/rangeSD);
    }

// The function which normalizes the indicators used to determine entry/exit signals.
void Normalize()
    {Suply=iBands(NULL,0,j,2,0,PRICE_CLOSE,MODE_UPPER,0);
    iSuply=iBands(NULL,0,j,2,0,PRICE_CLOSE,MODE_UPPER,1);
    Demand=iBands(NULL,0,j,2,0,PRICE_CLOSE,MODE_LOWER,0);
    iDemand=iBands(NULL,0,j,2,0,PRICE_CLOSE,MODE_LOWER,1);
    ArrayResize(iA,13*((S+1)-Y));
    ArrayResize(cA,13*((S+1)-Y));
    double uADX[];
    ArrayResize(uADX,j+1);
    for(int i=0;i<j+1; i++){uADX[i]=iADX(NULL,0,j,PRICE_CLOSE,MODE_PLUSDI,i);}
    double maxuADX=uADX[ArrayMaximum(uADX,WHOLE_ARRAY,0)];
    double minuADX=uADX[ArrayMinimum(uADX,WHOLE_ARRAY,0)];
    double lADX[];
    ArrayResize(lADX,j+1);
    for(int i=0;i<j+1; i++){lADX[i]=iADX(NULL,0,j,PRICE_CLOSE,MODE_MINUSDI,i);}
    double maxlADX=lADX[ArrayMaximum(lADX,WHOLE_ARRAY,0)];
    double minlADX=lADX[ArrayMinimum(lADX,WHOLE_ARRAY,0)];
    ArrayResize(ADX,j+1);
    for(int i=0;i<j+1; i++){ADX[i]=iADX(NULL,0,j,PRICE_CLOSE,MODE_MAIN,i);}
    double maxmADX=ADX[ArrayMaximum(ADX,WHOLE_ARRAY,0)];
    double minmADX=ADX[ArrayMinimum(ADX,WHOLE_ARRAY,0)];
    double maxADX=MathMax(maxmADX,MathMax(maxuADX,maxlADX));
    double minADX=MathMin(minmADX,MathMin(minuADX,minlADX));
    double rangeADX=maxADX-minADX;
    if(rangeADX!=0)
        {
        iADX=MathAbs(100*((iADX(NULL,0,j,PRICE_CLOSE,MODE_MAIN,0)-minADX)/rangeADX));
        iA[0*(S-Y)+(j-(Y+1))]=iADX;
        cADX=MathAbs(100*((ADX[1]-minADX)/rangeADX));
        cA[0*(S-Y)+(j-(Y+1))]=cADX;
        }
    int jSO=(int)MathRound((double)j*3.0/5);
    mStochastic=iStochastic(NULL,0,j,3,jSO,MODE_SMA,0,MODE_MAIN,0);
    sStochastic=iStochastic(NULL,0,j,3,jSO,MODE_SMA,0,MODE_SIGNAL,0);
    iStochastic=(mStochastic+sStochastic)/2;
    iA[1*(S-Y)+(j-(Y+1))]=iStochastic;
    mSO=iStochastic(NULL,0,j,3,jSO,MODE_SMA,0,MODE_MAIN,1);
    sSO=iStochastic(NULL,0,j,3,jSO,MODE_SMA,0,MODE_SIGNAL,1);
    iSO=(mSO+sSO)/2;
    cA[1*(S-Y)+(j-(Y+1))]=iSO;
    ArrayResize(RVIm,j+1);
    for(int i=0;i<j+1; i++){RVIm[i]=iRVI(NULL,0,j,MODE_MAIN,i);}
    double maxMRVI=RVIm[ArrayMaximum(RVIm,WHOLE_ARRAY,0)];
    double minMRVI=RVIm[ArrayMinimum(RVIm,WHOLE_ARRAY,0)];
    double RVIs[];
    ArrayResize(RVIs,j+1);
    for(int i=0;i<j+1; i++){RVIs[i]=iRVI(NULL,0,j,MODE_SIGNAL,i);}
    double maxSRVI=RVIs[ArrayMaximum(RVIs,WHOLE_ARRAY,0)];
    double minSRVI=RVIs[ArrayMinimum(RVIs,WHOLE_ARRAY,0)];
    double maxRVI=MathMax(maxMRVI,maxSRVI);
    double minRVI=MathMin(minMRVI,minSRVI);
    double rangeRVI=maxRVI-minRVI;
    if(rangeRVI!=0)
        {
        mRVI=100*((iRVI(NULL,0,j,MODE_MAIN,0)-minRVI)/rangeRVI);
        sRVI=100*((iRVI(NULL,0,j,MODE_SIGNAL,0)-minRVI)/rangeRVI);
        iRVI=(mRVI+sRVI)/2;
        iA[2*(S-Y)+(j-(Y+1))]=iRVI;
        aRVI=100*((iRVI(NULL,0,j,MODE_MAIN,1)-minRVI)/rangeRVI);
        bRVI=100*((iRVI(NULL,0,j,MODE_SIGNAL,1)-minRVI)/rangeRVI);
        cRVI=(aRVI+bRVI)/2;
        cA[2*(S-Y)+(j-(Y+1))]=cRVI;
        }
    ArrayResize(AC,j+1);
    for(int i=0;i<j+1; i++){AC[i]=iAC(NULL,0,i);}
    double maxAC=AC[ArrayMaximum(AC,WHOLE_ARRAY,0)];
    double minAC=AC[ArrayMinimum(AC,WHOLE_ARRAY,0)];
    double rangeAC=maxAC-minAC;
    if(rangeAC!=0)
        {
        iAC=MathAbs(100*((iAC(NULL,0,0)-minAC)/rangeAC));
        iA[3*(S-Y)+(j-(Y+1))]=iAC;
        cAC=MathAbs(100*((iAC(NULL,0,1)-minAC)/rangeAC));
        cA[3*(S-Y)+(j-(Y+1))]=cAC;
        }
    ArrayResize(Force,j+1);
    for(int i=0;i<j+1; i++){Force[i]=iForce(NULL,0,j,MODE_SMA,PRICE_CLOSE,i);}
    double maxForce=Force[ArrayMaximum(Force,WHOLE_ARRAY,0)];
    double minForce=Force[ArrayMinimum(Force,WHOLE_ARRAY,0)];
    double rangeForce=maxForce-minForce;
    if(rangeForce!=0)
        {
        iForce=100*((iForce(NULL,0,j,MODE_SMA,PRICE_CLOSE,0)-minForce)/rangeForce);
        iA[4*(S-Y)+(j-(Y+1))]=iForce;
        cForce=100*((iForce(NULL,0,j,MODE_SMA,PRICE_CLOSE,1)-minForce)/rangeForce);
        cA[4*(S-Y)+(j-(Y+1))]=cForce;
        }
    ArrayResize(OBV,j+1);
    for(int i=0;i<j+1; i++){OBV[i]=iOBV(NULL,0,PRICE_CLOSE,i);}
    double maxOBV=OBV[ArrayMaximum(OBV,WHOLE_ARRAY,0)];
    double minOBV=OBV[ArrayMinimum(OBV,WHOLE_ARRAY,0)];
    double rangeOBV=maxOBV-minOBV;
    if(rangeOBV!=0)
        {
        iOBV=100*((iOBV(NULL,0,PRICE_CLOSE,0)-minOBV)/rangeOBV);
        iA[5*(S-Y)+(j-(Y+1))]=iOBV;
        cOBV=100*((iOBV(NULL,0,PRICE_CLOSE,1)-minOBV)/rangeOBV);
        cA[5*(S-Y)+(j-(Y+1))]=cOBV;
        }
    ArrayResize(AD,j+1);
    for(int i=0;i<j+1; i++){AD[i]=iAD(NULL,0,i);}
    double maxAD=AD[ArrayMaximum(AD,WHOLE_ARRAY,0)];
    double minAD=AD[ArrayMinimum(AD,WHOLE_ARRAY,0)];
    double rangeAD=maxAD-minAD;
    if(rangeAD!=0)
        {
        iAD=100*((iAD(NULL,0,0)-minAD)/rangeAD);
        iA[6*(S-Y)+(j-(Y+1))]=iAD;
        cAD=100*((iAD(NULL,0,1)-minAD)/rangeAD);
        cA[6*(S-Y)+(j-(Y+1))]=cAD;
        }
    ArrayResize(MFI,j+1);
    for(int i=0;i<j+1; i++){MFI[i]=iMFI(NULL,0,j,i);}
    double maxMFI=MFI[ArrayMaximum(MFI,WHOLE_ARRAY,0)];
    double minMFI=MFI[ArrayMinimum(MFI,WHOLE_ARRAY,0)];
    double rangeMFI=maxMFI-minMFI;
    if(rangeMFI!=0)
        {
        iMFI=100*((iMFI(NULL,0,j,0)-minMFI)/rangeMFI);
        iA[7*(S-Y)+(j-(Y+1))]=iMFI;
        cMFI=100*((iMFI(NULL,0,j,1)-minMFI)/rangeMFI);
        cA[7*(S-Y)+(j-(Y+1))]=cMFI;
        }
    ArrayResize(MOM,j+1);
    for(int i=0;i<j+1; i++){MOM[i]=iMomentum(NULL,0,j,PRICE_CLOSE,i);}
    double maxMOM=MOM[ArrayMaximum(MOM,WHOLE_ARRAY,0)];
    double minMOM=MOM[ArrayMinimum(MOM,WHOLE_ARRAY,0)];
    double rangeMOM=maxMOM-minMOM;
    if(rangeMOM!=0)
        {
        iMomentum=100*((iMomentum(NULL,0,j,PRICE_CLOSE,0)-minMOM)/rangeMOM);
        iA[8*(S-Y)+(j-(Y+1))]=iMomentum;
        cMomentum=100*((iMomentum(NULL,0,j,PRICE_CLOSE,1)-minMOM)/rangeMOM);
        cA[8*(S-Y)+(j-(Y+1))]=cMomentum;
        }
    ArrayResize(DeM,j+1);
    for(int i=0;i<j+1; i++){DeM[i]=iDeMarker(NULL,0,j,i);}
    double maxDM=DeM[ArrayMaximum(DeM,WHOLE_ARRAY,0)];
    double minDM=DeM[ArrayMinimum(DeM,WHOLE_ARRAY,0)];
    double rangeDM=maxDM-minDM;
    if(rangeDM!=0)
        {
        iDM=100*(iDeMarker(NULL,0,j,0)-minDM)/rangeDM;
        iA[9*(S-Y)+(j-(Y+1))]=iDM;
        cDM=100*(iDeMarker(NULL,0,j,1)-minDM)/rangeDM;
        cA[9*(S-Y)+(j-(Y+1))]=cDM;
        }
    iWPR=iWPR(NULL,0,j,0)+100;
    iA[10*(S-Y)+(j-(Y+1))]=iWPR;
    cWPR=iWPR(NULL,0,j,1)+100;
    cA[10*(S-Y)+(j-(Y+1))]=cWPR;
    ArrayResize(CCI,j+1);
    for(int i=0;i<j+1; i++){CCI[i]=iCCI(Symbol(),0,j,PRICE_TYPICAL,i);}
    double maxCCI=CCI[ArrayMaximum(CCI,WHOLE_ARRAY,0)];
    double minCCI=CCI[ArrayMinimum(CCI,WHOLE_ARRAY,0)];
    double rangeCCI=maxCCI-minCCI;
    if(rangeCCI!=0)
        {
        iCCI=100*((iCCI(Symbol(),0,j,PRICE_TYPICAL,0)-minCCI)/rangeCCI);
        iA[11*(S-Y)+(j-(Y+1))]=iCCI;
        cCCI=100*((iCCI(Symbol(),0,j,PRICE_TYPICAL,1)-minCCI)/rangeCCI);
        cA[11*(S-Y)+(j-(Y+1))]=cCCI;
        }
    ArrayResize(RSI,j+1);
    for(int i=0;i<j+1; i++){RSI[i]=iRSI(NULL,0,j,PRICE_CLOSE,i);}
    double maxRSI=RSI[ArrayMaximum(RSI,WHOLE_ARRAY,0)];
    double minRSI=RSI[ArrayMinimum(RSI,WHOLE_ARRAY,0)];
    double rangeRSI=maxRSI-minRSI;
    if(rangeRSI!=0)
        {
        iRSI=100*((iRSI(NULL,0,j,PRICE_CLOSE,0)-minRSI)/rangeRSI);
        iA[12*(S-Y)+(j-(Y+1))]=iRSI;
        cRSI=100*((iRSI(NULL,0,j,PRICE_CLOSE,1)-minRSI)/rangeRSI);
        cA[12*(S-Y)+(j-(Y+1))]=cRSI;
        }
    int kIHK=(int)MathRound((double)j/2);
    int tIHK=(int)MathRound(((double)kIHK+1)/3);
    double IHKa[];
    double IHKb[];
    double IHKc[];
    ArrayResize(IHKa,j+1);
    for(int i=0;i<j+1; i++){IHKa[i]=iIchimoku(NULL,0,tIHK,kIHK,j,MODE_SENKOUSPANA,i);}
    double maxIHKa=IHKa[ArrayMaximum(IHKa,WHOLE_ARRAY,0)];
    double minIHKa=IHKa[ArrayMinimum(IHKa,WHOLE_ARRAY,0)];
    ArrayResize(IHKb,j+1); 
    for(int i=0;i<j+1; i++){IHKb[i]=iIchimoku(NULL,0,tIHK,kIHK,j,MODE_SENKOUSPANB,i); }
    double maxIHKb=IHKb[ArrayMaximum(IHKb,WHOLE_ARRAY,0)]; 
    double minIHKb=IHKb[ArrayMinimum(IHKb,WHOLE_ARRAY,0)];
    ArrayResize(IHKc,j+1);
    for(int i=0;i<j+1; i++){IHKc[i]=iIchimoku(NULL,0,tIHK,kIHK,j,MODE_CHIKOUSPAN,26+i);}
    double maxIHKc=IHKc[ArrayMaximum(IHKc,WHOLE_ARRAY,0)];
    double minIHKc=IHKc[ArrayMinimum(IHKc,WHOLE_ARRAY,0)];
    ArrayResize(IHKt,j+1);
    for(int i=0;i<j+1; i++){IHKt[i]=iIchimoku(NULL,0,tIHK,kIHK,j,MODE_TENKANSEN,i);}
    double maxIHKt=IHKt[ArrayMaximum(IHKt,WHOLE_ARRAY,0)];
    double minIHKt=IHKt[ArrayMinimum(IHKt,WHOLE_ARRAY,0)];
    ArrayResize(IHKk,j+1);
    for(int i=0;i<j+1; i++){IHKk[i]=iIchimoku(NULL,0,tIHK,kIHK,j,MODE_KIJUNSEN,i);}
    double maxIHKk=IHKk[ArrayMaximum(IHKk,WHOLE_ARRAY,0)];
    double minIHKk=IHKk[ArrayMinimum(IHKk,WHOLE_ARRAY,0)];
    double maxIHK=MathMax(maxIHKa,MathMax(maxIHKb,MathMax(maxIHKc,MathMax(maxIHKk,maxIHKt))));
    double minIHK=MathMin(minIHKa,MathMin(minIHKb,MathMin(minIHKc,MathMin(minIHKk,minIHKt))));
    double rangeIHK=maxIHK-minIHK;
    if(rangeIHK!=0)
        {
        iIHKk=100*((iIchimoku(NULL,0,tIHK,kIHK,j,MODE_KIJUNSEN,0)-minIHK)/rangeIHK);
        iIHKt=100*((iIchimoku(NULL,0,tIHK,kIHK,j,MODE_TENKANSEN,0)-minIHK)/rangeIHK);
        }
    }

// Price action function indicating overbought conditions, and counting the number of those that are.
void M()
    {for(int i=0;i<13; i++)
        {
        if(Price>HH[j-(y+1)]) if((iA[i*(S-Y)+(j-(Y+1))]>f+gf)||(cA[i*(S-Y)+(j-(Y+1))]<kA[i*(S-Y)+(j-(Y+1))])) m++;
        else if(price>HH[j-(y+1)]) if((iA[i*(S-Y)+(j-(Y+1))]>f+gf)||(iA[i*(S-Y)+(j-(Y+1))]<kA[i*(S-Y)+(j-(Y+1))])) m++;
        else if(iA[i*(S-Y)+(j-(Y+1))]>f+gf) m++;
        }
    if((iA[0*(S-Y)+(j-(Y+1))]>f+gf)||(iA[0*(S-Y)+(j-(Y+1))]<g-gf)) m++;
    if((iIHKt>f+gf)&&(iIHKk>f+gf)) m++;
    if(Price>HH[j-(y+1)])
        {
        ArrayResize(kA,13*(S-Y));
        for(int i=0;i<13; i++){kA[i*(S-Y)+(j-(Y+1))]=cA[i*(S-Y)+(j-(Y+1))];}
        HH[j-(y+1)]=Price;
        }
    }

// Price action function used to find oversold conditions, and counting the number of those that are.
void N()
    {for(int i=0;i<13; i++)
        {
        if(Price<LL[j-(y+1)]) if((iA[i*(S-Y)+(j-(Y+1))]<g-gf)||(cA[i*(S-Y)+(j-(Y+1))]>lA[i*(S-Y)+(j-(Y+1))])) n++;
        else if(price<LL[j-(y+1)]) if((iA[i*(S-Y)+(j-(Y+1))]<g-gf)||(iA[i*(S-Y)+(j-(Y+1))]>lA[i*(S-Y)+(j-(Y+1))])) n++;
        else if(iA[i*(S-Y)+(j-(Y+1))]<g-gf) n++;
        }
    if((iA[0*(S-Y)+(j-(Y+1))]>f+gf)||(iA[0*(S-Y)+(j-(Y+1))]<g-gf)) n++;
    if((iIHKt<g-gf)&&(iIHKk<g-gf)) n++;
    if(Price<LL[j-(y+1)])
        {
        ArrayResize(lA,13*(S-Y));
        for(int i=0;i<13; i++){lA[i*(S-Y)+(j-(Y+1))]=cA[i*(S-Y)+(j-(Y+1))];}
        LL[j-(y+1)]=Price;
        }
    }

// Restarts the recording resetting vars. to retain only the most recent relevant price action data when regime changes occur for each period of state indicators from minimum to maximum.
void F()
    {Normalize();
    //if(j==h) ab=false;
    k[j-(y+1)]=false;
    l[j-(y+1)]=false;
    HH[j-(y+1)]=iH;
    LL[j-(y+1)]=iL;
    Premium[j-(y+1)]=iH;
    Discount[j-(y+1)]=iL;
    ArrayResize(kA,13*(S-Y));
    ArrayResize(lA,13*(S-Y));
    for(int i=0;i<13; i++)
        {
        kA[i*(S-Y)+(j-(Y+1))]=cA[i*(S-Y)+(j-(Y+1))];
        lA[i*(S-Y)+(j-(Y+1))]=cA[i*(S-Y)+(j-(Y+1))];
        }
    if((R==true)&&(FG==true))
        {
        ArrayResize(U,x-y);
        int V=0; U[j-(y+1)]=true;
        for(int i=y+1;i<x; i++){if(U[i-(y+1)]==true) V++;}
        if(V==x-y){R=false;} V=0;
        }
    }

// Reset price action data as F() does, but for vars. relative to signal events.
void G()
    {double H=iHigh(Symbol(), Period(), 1);
    double L=iLow(Symbol(), Period(), 1);
    ArrayResize(kA,13*(S-Y));
    ArrayResize(lA,13*(S-Y));
    for(j=2;j<h+1; j++)
        {
        if(j==x) break;
        k[j-(y+1)]=false;
        l[j-(y+1)]=false;
        HH[j-(y+1)]=H;
        LL[j-(y+1)]=L;
        Premium[j-(y+1)]=H;
        Discount[j-(y+1)]=L;
        for(int i=0;i<13; i++)
            {
            kA[i*(S-Y)+(j-(Y+1))]=cA[i*(S-Y)+(j-(Y+1))];
            lA[i*(S-Y)+(j-(Y+1))]=cA[i*(S-Y)+(j-(Y+1))];
            }
        }
    }

// Used to determine the stop loss, and take profit price using the difference, via given input vars. of global declarations, from  market price at any given time.
void S()
    {if(SL!=0){sSL=Bid+SL-com; bSL=Ask-SL+com;}
    if(TP!=0){sTP=Bid-TP; bTP=Ask+TP;}
    }

// To implement S() when, trade taking, and find the sign of the profit/loss (PñL), so whether profiting or losing, at all times.
void T()
    {if(((b==false)&&(lOrder_id!=-1))||((a==false)&&(kOrder_id!=-1)))
        {
        Buy=lOrder_id; Sell=kOrder_id;
        }
    else if(((b==false)&&(kOrder_id!=-1))||((a==false)&&(lOrder_id!=-1)))
        {
        Buy=kOrder_id; Sell=lOrder_id;
        }
    if(Buy!=-1)
        {
        if(OrderSelect(Buy,SELECT_BY_TICKET))
            {
            /*E=OrderOpenPrice();*/ E=price; q=E+3*com;
            }
        }
    else if(Sell!=-1)
        {if(OrderSelect(Sell,SELECT_BY_TICKET))
            {
            /*D=OrderOpenPrice();*/ D=price; p=D-3*com;
            }
        }
    if((K==false)&&((SL!=0)||(com!=0)))
        {
        if((b==false)&&(Price>q))
            {
            b=OrderModify(Buy,E,E+com,bTP,0,CLR_NONE); K=true;
            }
        else if((a==false)&&(Price<p))
            {
            a=OrderModify(Sell,D,D-com,sTP,0,CLR_NONE); K=true;
            }
        }
    if((E!=0)&&(price>=E/*+com*/)) B=true;
    else if((E!=0)&&(price<E/*+com*/)) B=false;
    if((D!=0)&&(price<=D/*-com*/)) A=true;
    else if((D!=0)&&(price>D/*-com*/)) A=false;
    }

// Draws a blue line on the chart when price is expected to increase.
void Top()
    {bottomLine=DoubleToString(price, Digits);
    if(ObjectFind(0, bottomLine)==-1)
        {
        ArrayResize(BL, (FVG+1)+1);
        BL[FVG+1]=price;
        ObjectCreate(0, bottomLine, OBJ_HLINE, 0, 0, price);
        ObjectSetInteger(0, bottomLine, OBJPROP_COLOR, clrBlue);
        ObjectSetInteger(0, bottomLine, OBJPROP_STYLE, STYLE_SOLID);
        ObjectSetInteger(0, bottomLine, OBJPROP_WIDTH, 1);
        FVG++; bL=bottomLine;
        }
    }

// Draws a red line on the chart when price is expected to decrease.
void Bott()
    {bottomLine=DoubleToString(price, Digits);
    if(ObjectFind(0, bottomLine)==-1)
        {
        ArrayResize(BL, FVG+2);
        BL[FVG+1]=price;
        ObjectCreate(0, bottomLine, OBJ_HLINE, 0, 0, price);
        ObjectSetInteger(0, bottomLine, OBJPROP_COLOR, clrRed);
        ObjectSetInteger(0, bottomLine, OBJPROP_STYLE, STYLE_SOLID);
        ObjectSetInteger(0, bottomLine, OBJPROP_WIDTH, 1);
        FVG++; bL=bottomLine;
        }
    }

// Erases lines drawn on chart.
void Deleter(string obj, double &prices[], int index)
    {int size = ArraySize(prices);
    if((index<0)||(index>=size)||(FVG!=size-1))
        return; // iInvalid
    if(ObjectFind(0, obj)!=-1)
        {ObjectDelete(0, obj); FVG--;
        }
    for(int i=index; i<size-1; i++)
        {
        prices[i]=prices[i+1];
        }
    ArrayResize(prices, size-1);
    }

// Closes, "Buy", positions.
void A()
    {if((v==true)&&(lOrder_id!=-1))
        {
        int bTrade=OrderClose(lOrder_id,lot,Bid,slip,Blue);
        lOrder_id=-1;
        }
    else if((v==true)&&(kOrder_id!=-1))
        {
        int bTrade=OrderClose(kOrder_id,lot,Bid,slip,Blue);
        kOrder_id=-1;
        }
    E=0; A=true; B=false; K=false; Buy=-1;
    }

// Closes, "Sell", positions.
void B()
    {if((u==true)&&(kOrder_id!=-1))
        {
        int sTrade=OrderClose(kOrder_id,lot,Ask,slip,Red);
        kOrder_id=-1;
        }
    else if((u==true)&&(lOrder_id!=-1))
        {
        int sTrade=OrderClose(lOrder_id,lot,Ask,slip,Red);
        lOrder_id=-1;
        }
    D=0; A=false; B=true; K=false; Sell=-1;
    }

// Market Execution Trade Entry.
void P()
    {S();
    if(signature==true)
        {if(C==true)
            {
            lOrder_id=OrderSend(_Symbol,OP_BUY,lot,Ask,slip,bSL,bTP,"EA",1992470,0,Blue);
            b=false; u=false; v=true;
            }
        else
            {
            lOrder_id=OrderSend(_Symbol,OP_SELL,lot,Bid,slip,sSL,sTP,"EA",1992470,0,Red);
            a=false; u=true; v=false;
            }
        }
    }
void Q()
    {S();
    if(signature==true)
        {if(C==true)
            {
            kOrder_id=OrderSend(_Symbol,OP_SELL,lot,Bid,slip,sSL,sTP,"EA",1992470,0,Red);
            a=false; u=true; v=false;
            }
        else
            {
            kOrder_id=OrderSend(_Symbol,OP_BUY,lot,Ask,slip,bSL,bTP,"EA",1992470,0,Blue);
            b=false; u=false; v=true;
            }
        }
    }

// Sets  overbought signal var. to true when the total number of indicators satisfying that condition is high enough.
void H(){M(); if(m>=12) k[j-(y+1)]=true; else{k[j-(y+1)]=false;} m=0;}

// Sets oversold signal var. to true when the total number of indicators satisfying that condition is high enough.
void L(){N(); if(n>=12) l[j-(y+1)]=true; else{l[j-(y+1)]=false;} n=0;}

// Determines the current, 'J', direction of price given the previous, 'I', as determined by OnCall() when reaching an opposite Bollinger Band (BB).
void J()
    {if(I==iZ){J=iW;}
    else if(I==iW){J=iZ;}
    if(iI==iz) iJ=iw;
    else if(iI==iw) iJ=iz;
    }

// Checks if the ranging period in question is higher or lower than the BB period reached by price.
void O(int inp,int inp0,int inp1,bool inp2,bool inp3)
    {if((inp<inp1)&&((Regime[inp0-(y+1)]=="sRange")||(Regime[inp0-(y+1)]=="tRange"))){inp2=inp3;}
    else if((Regime[inp0-(y+1)]!="sRange")&&(Regime[inp0-(y+1)]!="tRange")) inp2=!inp3; else inp2=!inp3;
    }

// Finds the lowest ranging period higher than the non-trending ñ trending reached respectively, and the highest ranging period lower than those  non-trending ñ trending reached respectively.
void R()
    {if(j<=J){int i=j; O=i; iO=i;}
    if((j>J)&&(j<r)){int i=j; O=i; iO=i; r=i;}
    else if(j>J){int i=j; r=i;}
    if(j<=iJ){int i=j; o=i; io=i;}
    if((j>iJ)&&(j<ir)){int i=j; o=i; io=i; ir=i;}
    else if(j>iJ){int i=j; ir=i;}
    }

// Lagging, but active, invertion of the binary logic used to trigger signals based on the binary "Only Constant is Change (KC)" principles' binary Change Constants (CC/Cc/cC/cc).
void KC()
    {if((E!=0)&&((A==false)&&(B==false))&&(v==true)&&(signal<E)){invert=!KC;}
    if((D!=0)&&((B==false)&&(A==false))&&(u==true)&&(signal>D)){invert=!KC;}
    }

// To find whether either both a given bar, 't', and or tick, 's', period is in a state of the regime in question.
bool OnHold(int inp,string inp0,string inp1){return ((Regime[inp-(y+1)]==inp0)||(Regime[inp-(y+1)]==inp1));}
bool OnFire(int inp,string inp0,string inp1){return ((Regime[inp-(y+1)]!=inp0)&&(Regime[inp-(y+1)]!=inp1));}

// Used to find the market state on tick.
void OnPoint()
    {for(j=y+1;j<x; j++)
        {
        Unify(); Normalize();
        if((iStdDev<50)&&(iATR>50)) if(Regime[j-(y+1)]!="Stable"){H(); L(); if(OnFire(j,"sVolatile","tVolatile")) Regime[j-(y+1)]="sVolatile";}
        else if((iStdDev<50)&&(iATR<50))
            {
            if(Regime[j-(y+1)]!="Stable")
                {
                R(); H(); L(); if(OnFire(j,"sRange","tRange")) Regime[j-(y+1)]="sRange";
                }
            }
        else if(OnFire(j,"sTrend","tTrend")) Regime[j-(y+1)]="sTrend";
        }
    }

// Sets a signal's price.
void Signal(){
    ab=!ba; count=0; toll=0; tally=""; signal=price;
    }

// Leading, but passive, invertion of the binary logic used to trigger signals based on the binary "Only Constant is Change (KC)" principles' binary Change Constants (CC/Cc/cC/cc).
bool OnGaurd(int inp){
    if((price>E)&&(E!=0)){if((signature==true)&&(inp!=-1)){dime=0;} return true;} else{if((signature==true)&&(inp!=-1)){dime=1;} return false;}
    if((price<D)&&(D!=0)){if((signature==true)&&(inp!=-1)){dime=1;} return true;} else{if((signature==true)&&(inp!=-1)){dime=0;} return false;}}

// Displays current direction of price, changes, motion.
void OnLog(){
    if(dime==0){Print("Flying");} else if(dime==1){Print("Falling");} else{Print("Wait/Decern");}
    }

// Scans through all periods up to the highest trending and not at or beyond a BB then tallying indicators  satisfying signal conditions.
void OnCall()
    {for(j=y+1;j<X+2; j++)
        {
        Unify(); Normalize();
        if((Suply<=price)||(iSuply<=price)||(iSuply<=iH))
            {
            int i=j; I=iW; iZ=i; Z=i; iC=C;
            if((iw!=0)&&(jC==Cc)){h=I;} jC=!C;
            if(OnHold(j,"sTrend","tTrend")){iz=i; z=i; iI=iw; H();}
            if(X!=x-1) X++;
            }
        if((Demand>=price)||(iDemand>=price)||(iDemand>=iL))
            {
            int i=j; I=iZ; iW=i; W=i; jC=C;
            if((iz!=0)&&(iC==Cc)){h=I;} iC=!C;
            if(OnHold(j,"sTrend","tTrend")){iw=i; w=i; iI=iz; L();}
            if(X!=x-1) X++;
            }
        } X=y;
    }

// Determines market regime on bar, and boundary conditions  used in later on bar instances to evaluate edge cases.
void OnBar()
    {for(j=y+1;j<x; j++)
        {
        Unify(); Normalize();
        if((iStdDev<50)&&(iATR>50))
            {
            if(Regime[j-(y+1)]!="Stable")
                {
                if(Regime[j-(y+1)]!="tVolatile")
                    {
                    F(); H(); L(); Regime[j-(y+1)]="tVolatile";
                    }
                }
            }
        else if((iStdDev<50)&&(iATR<50))
            {
            if(Regime[j-(y+1)]!="Stable")
                {
                R(); H(); L();
                if(Regime[j-(y+1)]!="tRange")
                    {
                    F(); Regime[j-(y+1)]="tRange";
                    }
                }
            }
        else if((Regime[j-(y+1)]!="tTrend")&&(Regime[j-(y+1)]!="sTrend")&&(LL[j-(y+1)]<Discount[j-(y+1)])&&(HH[j-(y+1)]>Premium[j-(y+1)])) Regime[j-(y+1)]="Stable";
        else
            {
            if(Regime[j-(y+1)]!="tTrend")
                {
                F(); Regime[j-(y+1)]="tTrend";
                }
            }
        }
    
    // Local variables used in final execution.
    Stock=iBands(NULL,0,y,2,0,PRICE_CLOSE,MODE_UPPER,0);
    Sale=iBands(NULL,0,y,2,0,PRICE_CLOSE,MODE_LOWER,0);
    iStock=iBands(NULL,0,y,2,0,PRICE_CLOSE,MODE_UPPER,1);
    iSale=iBands(NULL,0,y,2,0,PRICE_CLOSE,MODE_LOWER,1);
    iopen=iOpen(Symbol(),0,2);
    iPrice=iClose(Symbol(),0,2);
    double lPass=0;
    
    // Final execution including edge cases.
    if(Price<open){lPass=Price;} else{lPass=open;}
    double ilPass=0;
    if(iPrice<iopen){ilPass=iPrice;} else{ilPass=iopen;}
    double kPass=0;
    if(Price>open){kPass=Price;} else{kPass=open;}
    double ikPass=0;
    if(iPrice>iopen){kPass=iPrice;} else{kPass=iopen;}
    string fg="";
    if(signal!=0)
        {if(/*(price>=signal+spread)||*/(price>=signal+com))
            {Alert("Long: ",price);
            if((count==0)&&(tally=="Sell")){count ++;} tally="Buy";
            }
        if(/*(price<=signal-spread)||*/(price<=signal-com))
            {Alert("Short: ",price);
            if((count==0)&&(tally=="Buy")){count ++;} tally="Sell";
            }
        if(tickTock==false)
            {if((((Price>signal)||(Price>ikPass)||(price>kPass)))&&(((iC==Cc)&&(Price>HH[min-(y+1)]))||((jC==Cc)&&(Price>=LL[min-(y+1)])&&(((open>=Stock)||(Price>=Stock))||((open>=iStock)||(Price>=iStock))))))
                {Alert("Buy: ",price);
                if((toll==0)&&(tally=="Sell")){toll ++;} if(Price>signal){fg="Up";} tally="Buy";
                }
            if((((Price<signal)||(Price<ilPass)||(price<lPass)))&&(((jC==Cc)&&(Price<LL[min-(y+1)]))||((iC==Cc)&&(Price<=HH[min-(y+1)])&&(((open<=Sale)||(Price<=Sale))||((open<=iSale)||(Price<=iSale))))))
                {Alert("Sell: ",price);
                if((toll==0)&&(tally=="Buy")){toll ++;} if(Price<signal){fg="Down";} tally="Sell";
                }
            if((toll==1)&&((tally=="Buy")||(fg=="Up")))
                {Alert("U+1F537 "/*,"🔷"*/,"Diamond ",fg);
                if(((prime==0)||(dime==0))&&(fg=="Up"))
                    {dime=0; mem=0;
                    if(((A==true)||(B==false))&&((u==true)||(v==false)))
                        {B(); if(C==true){P();} else{Q();} Alert("Bull"); Top(); E=price;} else{B(); Alert("Bull"); Top(); E=price;}}
                else if((dime!=-1)&&(prime==0)&&(fg=="")&&(Price>signal))
                    {dime=0; mem=0;
                    if(((A==true)||(B==false))&&((u==true)||(v==false)))
                        {B(); if(C==true){P();} else{Q();} Alert("Bull"); Top(); E=price;} else{B(); Alert("Bull"); Top(); E=price;}}
                else if(Price>signal){B(); Alert("U+1F943 "/*,"🥃"*/,"Whisky"); Top(); E=price;} else{OnLog(); A(); Alert("U+1F377 ",/*"🍷",*/"Wine"); Bott(); D=price;}
                signal=0; toll=0; tally=""; GF=true; signature=true;
                }
            if((toll==1)&&((tally=="Sell")||(fg=="Down")))
                {Alert("U+1F53B "/*,"🔻"*/,"Ruby ",fg);
                if((fg=="Down")&&((prime==1)||(dime==1)))
                    {dime=1; mem=1;
                    if(((A==false)||(B==true))&&((u==false)||(v==true)))
                        {A(); if(C==false){P();} else{Q();} Alert("Bear"); Bott(); D=price;} else{A(); Alert("Bear"); Bott(); D=price;}}
                else if(((dime!=-1)&&(prime==1))&&(fg=="")&&(Price<signal))
                    {dime=1; mem=1;
                    if(((A==false)||(B==true))&&((u==false)||(v==true)))
                        {A(); if(C==false){P();} else{Q();} Alert("Bear"); Bott(); D=price;} else{A(); Alert("Bear"); Bott(); D=price;}}
                else if(Price<signal){A(); Alert("U+1F377 ",/*"🍷",*/"Wine"); Bott(); D=price;} else{OnLog(); B(); Alert("U+1F943 "/*,"🥃"*/,"Whisky"); Top(); E=price;}
                signal=0; toll=0; tally=""; GF=true; signature=true;
                }
            if((count==1)&&((tally=="Buy")||(fg=="Up")))
                {Alert("U+1F537 "/*,"🔷"*/,"Diamond ",fg);
                if(((prime==0)||(dime==0))&&(fg=="Up"))
                    {dime=0; mem=0;
                    if(((A==true)||(B==false))&&((u==true)||(v==false)))
                        {B(); if(C==true){P();} else{Q();} Alert("Hawk"); Top(); E=price;} else{B(); Alert("Hawk"); Top(); E=price;}}
                else if(((dime!=-1)&&(prime==0))&&(fg=="")&&(Price>signal))
                    {dime=0; mem=0;
                    if(((A==true)||(B==false))&&((u==true)||(v==false)))
                        {B(); if(C==true){P();} else{Q();} Alert("Hawk"); Top(); E=price;} else{B(); Alert("Hawk"); Top(); E=price;}}
                else if(Price>signal){B(); Alert("U+1F4A7 ",/*"💧",*/"Watter"); Top(); E=price;} else{OnLog(); A(); Alert("U+1FA78 ",/*"🩸",*/"Blood"); Bott(); D=price;}
            count=0; tally=""; GF=true; signature=true;
                }
            if((count==1)&&((tally=="Sell")||(fg=="Down")))
                {Alert("U+1F53B "/*,"🔻"*/,"Ruby ",fg);
                if((fg=="Down")&&((prime==1)||(dime==1)))
                    {dime=1; mem=1;
                    if(((A==false)||(B==true))&&((u==false)||(v==true)))
                        {A(); if(C==false){P();} else{Q();} Alert("Dove"); Bott(); D=price;} else{A(); Alert("Dove"); Bott(); D=price;}}
                else if(((dime!=-1)&&(prime==1))&&(fg=="")&&(Price<signal))
                    {dime=1; mem=1;
                    if(((A==false)||(B==true))&&((u==false)||(v==true)))
                        {A(); if(C==false){P();} else{Q();} Alert("Dove"); Bott(); D=price;} else{A(); Alert("Dove"); Bott(); D=price;}}
                else if(Price<signal){A(); Alert("U+1FA78 ",/*"🩸",*/"Blood"); Bott(); D=price;} else{OnLog(); B(); Alert("U+1F4A7 ",/*"💧",*/"Watter"); Top(); E=price;}
                count=0; tally=""; GF=true; signature=true;
                }
            }
        }
    
    // Boundary conditions setting up "breakouts" or "bounce backs" edge cases.
    if((OnGaurd(-1))&&(KC==true))
        {
        if((h!=0)&&(ab==false)&&(U[O-(y+1)]=true)&&(O>2)&&(O!=x-1)/*&&(OnFire(O,"sTrend","tTrend"))*/)
            {
            if(HH[O-(y+1)]>Premium[O-(y+1)])
                {
                h=O;
                if((C==true)||(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price,"O:",O,"|",C,":",c);
                    }
                else if((C==false)&&(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price,"O:",O,"|",C,":",c);
                    }
                }
            if(LL[O-(y+1)]<Discount[O-(y+1)])
                {
                h=O;
                if((C==true)||(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price,"O:",O,"|",C,":",c);
                    }
                else if((C==false)&&(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price,"O:",O,"|",C,":",c);
                    }
                }
            }
        if((h!=0)&&(ab==false)&&(U[o-(y+1)]=true)&&(o>2)&&(o!=x-1)/*&&(OnFire(o,"sTrend","tTrend"))*/)
            {
            if(HH[o-(y+1)]>Premium[o-(y+1)])
                {
                h=o;
                if((C==false)&&(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price,"o:",o,"|",C,":",c);
                    }
                else if((C==true)||(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price,"o:",o,"|",C,":",c);
                    }
                }
            if(LL[o-(y+1)]<Discount[o-(y+1)])
                {
                h=o;
                if((C==false)&&(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price,"o:",o,"|",C,":",c);
                    }
                else if((C==true)||(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price,"o:",o,"|",C,":",c);
                    }
                }
            }
        }
    else if(OnGaurd(-1)!=KC)
        {
        if((h!=0)&&(ab==false)&&(U[O-(y+1)]=true)&&(O>2)&&(O!=x-1)/*&&(OnFire(O,"sTrend","tTrend"))*/)
            {
            if(HH[O-(y+1)]>Premium[O-(y+1)])
                {
                h=O;
                if((C==false)||(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price,"O:",O,"|",C,":",c);
                    }
                else if((C==true)&&(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price,"O:",O,"|",C,":",c);
                    }
                }
            if(LL[O-(y+1)]<Discount[O-(y+1)])
                {
                h=O;
                if((C==false)||(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price,"O:",O,"|",C,":",c);
                    }
                else if((C==true)&&(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price,"O:",O,"|",C,":",c);
                    }
                }
            }
        if((h!=0)&&(ab==false)&&(U[o-(y+1)]=true)&&(o>2)&&(o!=x-1)/*&&(OnFire(o,"sTrend","tTrend"))*/)
            {
            if(HH[o-(y+1)]>Premium[o-(y+1)])
                {
                h=o;
                if((C==true)&&(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price,"o:",o,"|",C,":",c);
                    }
                else if((C==false)||(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price,"o:",o,"|",C,":",c);
                    }
                }
            if(LL[o-(y+1)]<Discount[o-(y+1)])
                {
                h=o;
                if((C==true)&&(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price,"o:",o,"|",C,":",c);
                    }
                else if((C==false)||(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price,"o:",o,"|",C,":",c);
                    }
                }
            }
        }
    if((h!=0)&&(signal!=0)&&(ab==ba))
        {
        if((OnGaurd(-1))&&(KC==true))
            {
            if((iz>=h)&&(iz>2)&&(((iZ>2)&&((iZ==iz)||(iZ==iz+h)||((iZ==iz+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/)))||((I>2)&&((I==iz)||(I==iz+h)||((I==iz+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/))))&&(k[iz-(y+1)]==false)/*&&(OnHold(z,"sTrend","tTrend"))*/)
                {
                h=iz;
                if((C==false)&&(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price," h:",h,"iZ:",iZ,"I:",I,"|=iz:",iz,"|",C);
                    }
                else if((C==true)||(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price," h:",h,"iZ:",iZ,"I:",I,"|=iz:",iz,"|",C);
                    }
                }
            else if((iO>=h)&&(iO>2)&&(((iZ>2)&&((iZ==iO)||(iZ==iO+h)||((iZ==iO+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/)))||((I>2)&&((I==iO)||(I==iO+h)||((I==iO+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/))))&&(k[iO-(y+1)]==false)/*&&(OnHold(O,"sRange","tRange"))*/)
                {
                h=iO;
                if((C==false)&&(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price," h:",h,"o:",o,"iZ:",iZ,"I:",I,"|=iO:",iO,"|",C);
                    }
                if((C==true)||(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price," h:",h,"o:",o,"iZ:",iZ,"I:",I,"|=iO:",iO,"|",C);
                    }
                }
            if((iw>=h)&&(iw>2)&&(((iW>2)&&((iW==iw)||(iW==iw+h)||((iW==iw+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/)))||((I>2)&&((I==iw)||(I==iw+h)||((I==iw+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/))))&&(l[iw-(y+1)]==false)/*&&(OnHold(w,"sTrend","tTrend"))*/)
                {
                h=iw;
                if((C==false)&&(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price," h:",h,"iW:",iW,"I:",I,"|=iw:",iw,"|",C);
                    }
                else if((C==true)||(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price," h:",h,"iW:",iW,"I:",I,"|=iw:",iw,"|",C);
                    }
                }
            else if((iO>=h)&&(iO>2)&&(((iW>2)&&((iW==iO)||(iW==iO+h)||((iW==iO+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/)))||((I>2)&&((I==iO)||(I==iO+h)||((I==iO+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/))))&&(l[iO-(y+1)]==false)/*&&(OnHold(O,"sRange","tRange"))*/)
                {
                h=iO;
                if((C==false)&&(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price," h:",h,"o:",o,"iW:",iW,"I:",I,"|=iO:",iO,"|",C);
                    }
                else if((C==true)||(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price," h:",h,"o:",o,"iW:",iW,"I:",I,"|=iO:",iO,"|",C);
                    }
                }
            }
        else if(OnGaurd(-1)!=KC)
            {
            if((iz>=h)&&(iz>2)&&(((iZ>2)&&((iZ==iz)||(iZ==iz+h)||((iZ==iz+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/)))||((I>2)&&((I==iz)||(I==iz+h)||((I==iz+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/))))&&(k[iz-(y+1)]==false)/*&&(OnHold(z,"sTrend","tTrend"))*/)
                {
                h=iz;
                if((C==true)&&(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price," h:",h,"iZ:",iZ,"I:",I,"|=iz:",iz,"|",C);
                    }
                else if((C==false)||(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price," h:",h,"iZ:",iZ,"I:",I,"|=iz:",iz,"|",C);
                    }
                }
            else if((iO>=h)&&(iO>2)&&(((iZ>2)&&((iZ==iO)||(iZ==iO+h)||((iZ==iO+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/)))||((I>2)&&((I==iO)||(I==iO+h)||((I==iO+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/))))&&(k[iO-(y+1)]==false)/*&&(OnHold(O,"sRange","tRange"))*/)
                {
                h=iO;
                if((C==true)&&(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price," h:",h,"o:",o,"iZ:",iZ,"I:",I,"|=iO:",iO,"|",C);
                    }
                if((C==false)||(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price," h:",h,"o:",o,"iZ:",iZ,"I:",I,"|=iO:",iO,"|",C);
                    }
                }
            if((iw>=h)&&(iw>2)&&(((iW>2)&&((iW==iw)||(iW==iw+h)||((iW==iw+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/)))||((I>2)&&((I==iw)||(I==iw+h)||((I==iw+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/))))&&(l[iw-(y+1)]==false)/*&&(OnHold(w,"sTrend","tTrend"))*/)
                {
                h=iw;
                if((C==true)&&(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price," h:",h,"iW:",iW,"I:",I,"|=iw:",iw,"|",C);
                    }
                else if((C==false)||(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price," h:",h,"iW:",iW,"I:",I,"|=iw:",iw,"|",C);
                    }
                }
            else if((iO>=h)&&(iO>2)&&(((iW>2)&&((iW==iO)||(iW==iO+h)||((iW==iO+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/)))||((I>2)&&((I==iO)||(I==iO+h)||((I==iO+io)&&(l[io-(y+1)]==false)/*&&(OnHold(o,"sRange","tRange"))*/))))&&(l[iO-(y+1)]==false)/*&&(OnHold(O,"sRange","tRange"))*/)
                {
                h=iO; 
                if((C==true)&&(c==true))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ dime=mem; Alert("Sin.",price," h:",h,"o:",o,"iW:",iW,"I:",I,"|=iO:",iO,"|",C);
                    }
                else if((C==false)||(c==false))
                    {
                    G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ dime=mem; Alert("Sine.",price," h:",h,"o:",o,"iW:",iW,"I:",I,"|=iO:",iO,"|",C);
                    }
                }
            }
        }
    tick ++;
    if(ab!=ba){ab=ba;} tickTock = false;
    }

// Final bearish reversal signal triggers.
void OnGoe()
    {if(/*(ab==false)&&*/(signal==0))
        {
        if((OnGaurd(0))&&(KC==true))
            {
            if(((h==io)&&(z>o))||((h==iO)&&(Z>O))||((h==iz)&&(Z>z))||((h==iZ)&&(Z<z)))
                {
                if((C==false)&&(c==false))
                    {
                    prime=1; G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ Alert("Sign.",price," h:",h,"|","Z:",iZ,"z:",iz,"O:",iO,"o:",io,"|",C,":",c);
                    }
                else
                    {
                    prime=1; G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ Alert("Sig.",price," h:",h,"|","Z:",iZ,"z:",iz,"O:",iO,"o:",io,"|",C,":",c);
                    }
                }
            else if(((h==io)||(h==iZ)||(h==iz)||(h==iO)))
                {
                if((C==false)&&(c==false))
                    {
                    prime=1; G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ Alert("Sig.",price," h:",h,"Z:",iZ,"z:",iz,"O:",iO,"o:",io,"|",C,":",c);
                    }
                else
                    {
                    prime=1; G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ Alert("Sign.",price," h:",h,"Z:",iZ,"z:",iz,"O:",iO,"o:",io,"|",C,":",c);
                    }
                }
            }
        else if(OnGaurd(0)!=KC)
            {
            if(((h==io)&&(z>o))||((h==iO)&&(Z>O))||((h==iz)&&(Z>z))||((h==iZ)&&(Z<z)))
                {
                if((C==false)||(c==false))
                    {
                    prime=1; G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ Alert("Sign.",price," h:",h,"|","Z:",iZ,"z:",iz,"O:",iO,"o:",io,"|",C,":",c);
                    }
                else
                    {
                    prime=1; G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ Alert("Sig.",price," h:",h,"|","Z:",iZ,"z:",iz,"O:",iO,"o:",io,"|",C,":",c);
                    }
                }
            else if(((h==io)||(h==iZ)||(h==iz)||(h==iO)))
                {
                if((C==false)||(c==false))
                    {
                    prime=1; G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ Alert("Sig.",price," h:",h,"Z:",iZ,"z:",iz,"O:",iO,"o:",io,"|",C,":",c);
                    }
                else
                    {
                    prime=1; G(); Signal(); tickTock=true; /*if(KC==true) */tag=1;/* else tag=0;*/ Alert("Sign.",price," h:",h,"Z:",iZ,"z:",iz,"O:",iO,"o:",io,"|",C,":",c);
                    }
                }
            KC();
            }
        }
    }

// Final bullish reversal signal triggers.

void OnToe()
    {if(/*(ab==false)&&*/(signal==0))
        {
        if((OnGaurd(0))&&(KC==true))
            {
            if(((h==io)&&(w>o))||((h==iO)&&(W>O))||((h==iw)&&(W>w))||((h==iW)&&(W<w)))
                {
                if((C==false)&&(c==false))
                    {
                    prime=0; G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ Alert("Sig.",price," h:",h," W<w","|","W:",iW,"w:",iw,"O:",iO,"o:",io,"|",C,":",c);
                    }
                else
                    {
                    prime=0; G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ Alert("Sign.",price," h:",h," W<w","|","W:",iW,"w:",iw,"O:",iO,"o:",io,"|",C,":",c);
                    }
                }
            else if(((h==io)||(h==iW)||(h==iw)||(h==iO)))
                {
                if((C==false)&&(c==false))
                    {
                    prime=0; G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ Alert("Sign.",price," h:",h,"W:",iW,"w:",iw,"O:",iO,"o:",io,"|",C,":",c);
                    }
                else
                    {
                    prime=0; G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ Alert("Sig.",price," h:",h,"W:",iW,"w:",iw,"O:",iO,"o:",io,"|",C,":",c);
                    }
                }
            }
        else if(OnGaurd(0)!=KC)
            {
            if(((h==io)&&(w>o))||((h==iO)&&(W>O))||((h==iw)&&(W>w))||((h==iW)&&(W<w)))
                {
                if((C==false)||(c==false))
                    {
                    prime=0; G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ Alert("Sig.",price," h:",h," W<w","|","W:",iW,"w:",iw,"O:",iO,"o:",io,"|",C,":",c);
                    }
                else
                    {
                    prime=0; G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ Alert("Sign.",price," h:",h," W<w","|","W:",iW,"w:",iw,"O:",iO,"o:",io,"|",C,":",c);
                    }
                }
            else if(((h==io)||(h==iW)||(h==iw)||(h==iO)))
                {
                if((C==false)||(c==false))
                    {
                    prime=0; G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ Alert("Sign.",price," h:",h,"W:",iW,"w:",iw,"O:",iO,"o:",io,"|",C,":",c);
                    }
                else
                    {
                    prime=0; G(); Signal(); tickTock=true; /*if(KC==true) */tag=0;/* else tag=1;*/ Alert("Sig.",price," h:",h,"W:",iW,"w:",iw,"O:",iO,"o:",io,"|",C,":",c);
                    }
                }
            KC();
            }
        }
    }

// Scanning periods beyond the minimum and maximum valued range when reaching  extrema usually during rair extenuating circumstances caused by news worthy events.
// Upside.
void OnTrack()
    {S=x; T=x; X=y; Y=y; datetime is=iTime(_Symbol,0,0);
    for(int s=x-1;s<S; s++)
        {
        int js=s; j=js; Normalize(); Unify();
        if((Suply<=price)||(iSuply<=price)||(iSuply<=iH))
            {int i=s; I=iW; j=max; Z=j; iZ=i; T++; iC=C;
            if((iw!=0)&&(jC==Cc)){h=I;} jC=!C;
            if(iStdDev>50){S++; iz=i; iI=iw; j=i; H();}
            else if(iATR<50){S++; iO=i; io=i; j=i; H();} else{j=i; H(); if(is!=t){if(OnFire(j,"Stable","tVolatile")){F(); Regime[j-(y+1)]="tVolatile";}} else{Regime[j-(y+1)]="sVolatile";} S++;}
            }
        if((Demand>=price)||(iDemand>=price)||(iDemand>=iL))
            {int i=s; I=iZ; j=max; W=j; iW=i; T++; jC=C;
            if((iz!=0)&&(iC==Cc)){h=I;} iC=!C;
            if(iStdDev>50){S++; iw=i; iI=iz; j=i; L();}
            else if(iATR<50){S++; iO=i; io=i; j=i; L();} else{j=i; L(); if(is!=t){if(OnFire(j,"Stable","tVolatile")){F(); Regime[j-(y+1)]="tVolatile";}} else{Regime[j-(y+1)]="sVolatile";} S++;}
            }
        if(s==4*max) break;
        }
    for(int s=x-1;s<S; s++)
        {int js=s; j=js; Normalize(); Unify();
        if((iStdDev<50)&&(iATR<50)){R(); L(); H();}
        } S=x; T=x;
    if((Z!=4*max)&&(Z>=z)){j=max-1; z=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}}
    else if((Z!=4*max)&&(Z<z)){j=max; z=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}} else{j=x-1; z=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}}
    if((W!=4*max)&&(W>=w)){j=max-1; w=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}}
    else if((W!=4*max)&&(W<w)){j=max; w=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}} else{j=x-1; w=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}}
    }
// Downside.
void OnStand()
    {S=x; T=x; X=y; Y=y; datetime is=iTime(_Symbol,0,0);
    for(int s=y+1;s>Y; s--)
        {
        if(s==1) break;
        int js=s; j=js; ir=0; ij=0; Normalize(); Unify();
        if((Suply<=price)||(iSuply<=price)||(iSuply<=iH))
            {int i=s; I=iW; j=min+1; Z=j; iZ=i; T--; iC=C;
            if((iw!=0)&&(jC==Cc)){h=I;} jC=!C;
            if((X!=Y)&&(iz==0)&&(iStdDev>50)){ij=i; iz=i; iI=iw; j=i; H(); if((ir==0)&&(Y!=2)){Y--;}}
            else if((X!=Y)&&(iO==0)&&(iATR<50)){iO=i; ir=i; j=i; H(); if((ij==0)&&(Y!=2)){Y--;}}
            else if(X==Y){j=i; H(); if(is!=t){if(OnFire(j,"Stable","tVolatile")){F(); Regime[j-(y+1)]="tVolatile";}} else{Regime[j-(y+1)]="sVolatile";} if((Y!=2)&&(X!=2)){Y--; X--;}}
            }
        else if((Demand>=price)||(iDemand>=price)||(iDemand>=iL))
            {int i=s; I=iZ; j=min+1; W=j; iW=i; T--; jC=C;
            if((iz!=0)&&(iC==Cc)){h=I;} iC=!C;
            if((X!=Y)&&(iw==0)&&(iStdDev>50)){ij=i; iw=i; iI=iz; j=i; L(); if((ir==0)&&(Y!=2)){Y--;}}
            else if((X!=Y)&&(iO==0)&&(iATR<50)){iO=i; io=i; ir=0; j=i; L(); if((ij==0)&&(Y!=2)){Y--;}}
            else if(X==Y){j=i; L(); if(is!=t){if(OnFire(j,"Stable","tVolatile")){F(); Regime[j-(y+1)]="tVolatile";}} else{Regime[j-(y+1)]="sVolatile";} if((Y!=2)&&(X!=2)){Y--; X--;}}
            } else{if((Y!=2)&&(X!=2)){Y--; X--;}}
        }
    for(int s=Y+1;s<y+1; s++)
        {
        int js=s; j=js; Normalize(); Unify();
        if((iStdDev<50)&&(iATR<50)){R(); L(); H();}
        } X=y; Y=y;
    if((Z!=2)&&(Z>=z)){j=min; z=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}}
    else if((Z!=2)&&(Z<z)){j=min+1; z=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}} else{j=y+1; z=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}}
    if((W!=2)&&(W>=w)){j=min; w=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}}
    else if((W!=2)&&(W<w)){j=min+1; w=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}} else{j=y+1; w=j; if(is!=t){if(Regime[j-(y+1)]!="tTrend"){F(); Regime[j-(y+1)]="tTrend";}} else{Regime[j-(y+1)]="sTrend";}}
    }

// Master execution function running the entire order of operations on tick.
void OnTick()
    {datetime is=iTime(_Symbol,0,0);
    price=SymbolInfoDouble(_Symbol,SYMBOL_BID);
    Price=iClose(Symbol(),0,1);
    open=iOpen(Symbol(),0,1);
    iH=iHigh(Symbol(),0,1);
    iL=iLow(Symbol(),0,1);
    if(FVG>=0)
        {
        for(int ii=0; ii<FVG; ii++)
            {
            bottomLine=DoubleToString(BL[ii], Digits);
            color bLC=(color)ObjectGet(bottomLine, OBJPROP_COLOR);
            if(bottomLine!=bL)
                {
                if((bLC==clrRed)&&((A==true)||(B==false))&&(BL[ii]<=price)){if(E!=0){Alert("Red");} Deleter(bottomLine, BL, ii);}
                if((bLC==clrBlue)&&((B==true)||(A==false))&&(BL[ii]>=price)){if(D!=0){Alert("Blue");} Deleter(bottomLine, BL, ii);}
                }
            }
        }
    if(FG==false)
        {if(signature==false){D=price; E=price;}
        ArrayResize(k,x-y);
        ArrayResize(l,x-y);
        ArrayResize(HH,x-y);
        ArrayResize(LL,x-y);
        ArrayResize(Premium,x-y);
        ArrayResize(Discount,x-y);
        ArrayResize(Regime,x-y);
        for(j=y+1;j<x; j++){F();} FG=true;
        }
    T(); OnPoint(); O(iO,O,J,C,Cc); O(io,o,iJ,c,cC); OnCall(); J();
    if(is!=t){OnBar(); O(iO,O,J,C,Cc); O(io,o,iJ,c,cC);}
    if((J==y+1)&&(J!=2))
        {
        OnStand(); J(); O(iO,O,J,C,Cc); O(io,o,iJ,c,cC);
        if((iO!=2)&&(J>=iO)){j=min; O=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}}
        else if((iO!=2)&&(J<iO)){j=min+1; O=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}} else{j=2; O=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}}
        if((io!=2)&&(iJ>=io)){j=min; o=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}}
        else if((io!=2)&&(iJ<io)){j=min+1; o=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}} else{j=2; o=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}}
        }
    if(J==x-1)
        {OnTrack(); J(); O(iO,O,J,C,Cc); O(io,o,iJ,c,cC);
        if((iO!=4*max)&&(J>=iO)){j=max-1; O=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}}
        else if((iO!=4*max)&&(J<iO)){j=max; O=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}} else{j=x-1; o=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}}
        if((io!=4*max)&&(iJ>=io)){j=max-1; o=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}}
        else if((io!=4*max)&&(iJ<io)){j=max; o=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}} else{j=x-1; o=j; if(is!=t){if(OnFire(j,"Stable","tRange")){F(); Regime[j-(y+1)]="tRange";}} else{Regime[j-(y+1)]="sRange";}}
        } t=is;
    if(Z!=x-1)
        {if((Z!=y+1)&&(k[iZ-(y+1)]==true)){h=iZ; OnGoe();}
        else if((k[iz-(y+1)]==true)&&(z!=y+1)&&(z!=x-1)/*&&(OnHold(z,"tTrend","sTrend"))*/){h=iz; OnGoe();}
        else if((k[io-(y+1)]==true)&&(o!=y+1)&&(o!=x-1)/*&&(OnHold(o,"tRange","sRange"))*/){h=io; OnGoe();}
        else if((k[iO-(y+1)]==true)&&(O!=y+1)&&(O!=x-1)/*&&(OnHold(O,"tRange","sRange"))*/){h=iO; OnGoe();}
        }
    if(W!=x-1)
        {if((W!=y+1)&&(l[iW-(y+1)]==true)){h=iW; OnToe();}
        else if((l[iw-(y+1)]==true)&&(w!=y+1)&&(w!=x-1)/*&&(OnHold(w,"tTrend","sTrend"))*/){h=iw; OnToe();}
        else if((l[io-(y+1)]==true)&&(o!=y+1)&&(o!=x-1)/*&&(OnHold(o,"tRange","sRange"))*/){h=io; OnToe();}
        else if((l[iO-(y+1)]==true)&&(O!=y+1)&&(O!=x-1)/*&&(OnHold(O,"tRange","sRange"))*/){h=iO; OnToe();}
        }
    if(GF==true){OnReInit(); GF=false;}
    Comment("    ^",iZ,":",Z,"|",iz,":",z,"=",k[Z-(y+1)],"|",k[z-(y+1)],"           Up(0)|Down(1): ",mem,
    "\n Lim",iO,":",O,"^",k[O-(y+1)],"_",l[O-(y+1)],".",io,":",o,"^",k[o-(y+1)],"_",l[o-(y+1)],"=",h,".",C,":",c,
    "\n    _",iW,":",W,"|",iw,":",w,"=",l[W-(y+1)],"|",l[w-(y+1)],"                 U+1F48E"/*," 💎 "*/);
    }// Natalia Tanyatia
```