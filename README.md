# vm-buyers-up-auctions

This is the official code repo for [Bidding in Uniform Price Auctions for Value Maximizing Buyers](https://arxiv.org/abs/2406.03674). 

In this paper, we study the problem of bidding in uniform price auctions widely used in practice. Although these auctions are non-truthful for bidders with quasilinear utility functions, several empirical findings suggest that the auction format induces truthful bidding from the bidders. We attribute this difference in theory and practice to the assumption of the behavioral model of the bidders. In this pursuit, we study uniform price auctions in a repeated setting from the perspective of a value-maximizing buyer who aims to maximize their acquired cumulative value across T rounds, subject to per-round return-on-investment (RoI) constraints. For a RoI-constrained, value-maximizing buyer, we study a generalized version of the uniform bidding format, commonly used in practice, which we term as m-uniform bidding. To characterize the optimal m-uniform bid, we introduce and study the notion of universally feasible (UF) bidding policies, which are robust, meaning that RoI feasibility is obtained regardless of the competitors' bids. We show that the optimal class of UF bidding policies is essentially a generalization of truthful bidding policies, which depends only on the valuation curve of the bidder and target RoI. To measure the performance of UF bidding policies against the optimal bidding policy that is not necessarily UF, we introduce a metric called the Price of Universal Feasibility (PoUF) and establish that PoUF is at most 2, irrespective of m and the upper bound is tight. We further compare the generalized m-uniform bidding interface against the classical uniform bidding format under which m=1, showing the total value under m-uniform bidding increases at most by a factor of m. Numerical simulations on semi-synthetic data demonstrate that UF bidding policies perform significantly better than the derived theoretical bounds.

## Requirements
The entire code is written in Python 3.6. All the requirements are mentioned in `requirements.txt`. <br/>
They can be installed using `pip install -r requirements.txt`.

## How to Run

### Clean Data

### Price of Universal Feasibility and Impact of increasing m.

### Camera ready Plots


## Citation
If you find this repo useful in your research, please consider citing the following paper:

```
@article{golrezaei2024bidding,
  title={Bidding in Uniform Price Auctions for Value Maximizing Buyers},
  author={Golrezaei, Negin and Sahoo, Sourav},
  journal={arXiv preprint arXiv:2406.03674},
  year={2024}
}
```
