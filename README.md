# farrell-betacov

Applying the Elmasri et al. combined model (scaled-phylogeny + affinity) approach to predict Bat-Betacoronavirus associations using the Bat-CoV data merged with HP3. HP3 records are truncated to virual genus.

Source data are from ViromeNet/cleanbats_betacov commit 90498e3

Predictions for bat betacoronavirus hosts are in results/farrell_Predictions.csv

The model predicts links internal to the documented association networks, and bat hosts which appear in the phylogeny, but are not in the original data are added to the results file with NA as probability of interaction.
