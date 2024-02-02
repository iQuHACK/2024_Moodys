# iQuHACK 2024 - Moody's Challenge

Here you will learn the details that are needed in order to access and operate resources for this challenge. See **moodys_challenge** to read the challenge. Make sure to first read the instructions below.

## Working on qBraid
[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/iQuHACK/2024_Moodys.git)

While simulations and emulations of your program can be done locally on your computer, the Moody's challenge will require access to qBraid for quantum hardware and accelerated GPUs. 

So here are some guidelines:
1. To launch these materials on qBraid, first fork this repository and click the above `Launch on qBraid` button. It will take you to your qBraid Lab with the repository cloned.
2. Once cloned, open terminal (first icon in the **Other** column in Launcher) and `cd` into this repo. Set the repo's remote origin using the git clone url you copied in Step 1, and then create a new branch for your team:

```bash
cd  2024_Moodys
git remote set-url origin <url>
git branch <team_name>
git checkout <team_name>

```

3. <img align="right" width="43%" src="https://github.com/iQuHACK/2024_Moodys/assets/32727721/d8f7203e-417e-430e-92e2-1a8f65745289">  Use the environment manager (**ENVS** tab in the right sidebar) to [install environment](https://docs.qbraid.com/projects/lab/en/latest/lab/environments.html) "Moody's". The installation should take ~2 min.
4. Once the installation is complete, click **Activate** to [add a new ipykernel](https://docs.qbraid.com/projects/lab/en/latest/lab/kernels.html) for "Moody's".
5. From the **FILES** tab in the left sidebar, double-click on the `2024_Moodys` directory.
6. You are now ready to begin hacking, [submitting jobs](https://docs.qbraid.com/projects/lab/en/latest/lab/quantum_jobs.html), and using [GPUs](https://docs.qbraid.com/projects/lab/en/latest/lab/gpu.html)! Work with your team to complete the challenge listed above.

Please note, you will be provisioned credits before the hackathon for GPUs and QPUs.
**Strategize carefully and conduct back of the envelope estimates for your experiments before running**
- [Quantum jobs costs](https://aws.amazon.com/braket/pricing/) 
- GPU cost (Nvidia V100 1 vGPU 4.13 credits/min)

For other questions or additional help using qBraid, see [Lab User Guide](https://docs.qbraid.com/projects/lab/en/latest/lab/overview.html), or reach out on the IQuHack qBraid Slack Channel.

## Before submission

Make sure that you devote some time to prepare a brief presentation (5-10 mins) showing your work. This presentation will be presented on Sunday.
