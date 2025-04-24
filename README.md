# Executable Environment for OSF Project [9tnmv](https://osf.io/9tnmv/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Overcorrection for Social Categorization Information Moderates Impact Bias in Affective Forecasting

**Project Description:**
> Plural societies require individuals to forecast how others—both in-group and out-group members—will respond to gains and setbacks. Typically, greater information results in correction from inaccurate initial forecasts. By contrast to the typical palliative effects of more information, we find that that correcting for targets’ social categories result in more extreme, less accurate forecasts.  Forecasters in three experiments exhibited more impact bias in their affective forecasts for in-group and out-group members’ responses to positive and negative outcomes when provided with social categorization information about their target (e.g., a “Democrat” or “Republican”) than when provided with no category information (e.g., a “person”). Inducing time pressure reduced the extremity of forecasts for group-labeled targets but did not affect forecasts for unidentified targets, suggesting that the increased impact bias for identified group members was due to differences in correction rather than in intuitive predictions.

**Original OSF Page:** [https://osf.io/9tnmv/](https://osf.io/9tnmv/)

---

**Important Note:** The contents of the `9tnmv_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_9tnmv/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_9tnmv/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `9tnmv_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-9tnmv:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-9tnmv
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.
