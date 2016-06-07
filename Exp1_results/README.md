# Fixed covariates V.S. Random covariates

In this experiment, we will compare two different models: Expo-MF with fixed location covariates and Expo-MF with random location covariates.

## Experimental set up

### Dataset
* Yelp location only (20000 less users)
* Gowalla (6000 less users)

### Model
* Expo-MF with fixed location covariates
* Expo-MF with random location covariates

### Inference algorithm
Gibbs sampler initialized by EM algorithm.


| Gowalla    | Gibbs fixed cov | Gibbs random cov   |
| ---------- | --------------- | ------------------ |
| Recall@20  | 0.0289          | -------------      |
| Recall@50  | 0.0433l         | Content Cell       |
| NDCG       | 0.0237          | Content Cell       |
| MAP        | 0.0097          | Content Cell       |


|Yelp        | Gibbs fixed cov | Gibbs random cov   |
| ---------- | --------------- | ------------------ |
| Recall@20  | 0.0289          | -------------      |
| Recall@50  | 0.0433l         | Content Cell       |
| NDCG       | 0.0237          | Content Cell       |
| MAP        | 0.0097          | Content Cell       |
