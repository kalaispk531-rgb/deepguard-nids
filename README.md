# DeepGuard

Code and result files for "DeepGuard: A Lightweight CNN-BiLSTM-Attention Network for Network Intrusion Detection, with a Multi-Seed Study of Augmentation, Adversarial Fine-Tuning and Federated Learning".

## Files
- DeepGuard_Colab_Experiments (7).ipynb: NSL-KDD+ and UNSW-NB15 experiments
- DeepGuard_NF_ToN_IoT (3).ipynb: NF-ToN-IoT-v3 experiments
- tableA_main.csv: all methods, mean ± std over seeds
- tableB_ablation.csv: augmentation ablation
- tableC_adversarial.csv: FGSM / PGD accuracy
- tableD_federated.csv: centralised vs federated training
- architecture_ablation_nsl_kdd.csv, architecture_ablation_nf_ton_iot.csv: per-seed architecture ablation (seeds 42-46)

## How to run
Open a notebook in Google Colab with a GPU runtime and run all cells.
Datasets: NSL-KDD, UNSW-NB15 and NF-ToN-IoT-v3 must be downloaded from their official sources.
