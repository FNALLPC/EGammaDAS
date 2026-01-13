---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---

{% include gh_variables.html %}

> ## Links 
> * [CMSDAS at LPC2026](https://indico.cern.ch/e/cmsdas2026)
> * [EGamma shortEx github repo](https://github.com/FNALLPC/EGammaDAS)
> * [Slides](https://indico.cern.ch/event/1518299/contributions/6389404/attachments/3199051/5694797/CMSDAS2026_EGamma.pdf)
> * [CMS EGamma POG twiki](https://twiki.cern.ch/twiki/bin/view/CMS/EgammaPOG)
{: .callout}

> ## Prerequisites
> * Use the cmslpc computing cluster
> * Checkout git repositories (but you can do this during the session)
> * Access the grid via their CMS grid certificate. If you don't have it then follow this procedure [here](https://twiki.cern.ch/twiki/bin/view/CMSPublic/WorkBookStartingGrid#ObtainingCert)
{: .prereq}

## Goal of this exercise

During this short exercise students will learn the basics of electron and photon reconstruction in CMS. Students will gain familiarity with the fundamental components of reconstruction and identification, use common algorithms, and will be introduced to the general EGamma requirements of standard CMS analyses. This will be done using the values stored in the NanoAOD data tier and using the Coffea framework.

This exercise will introduce the participants to the reconstruction, identification and isolation of electrons and photons. In particular, we will cover:

 - The ideas of the reconstruction algorithms developed for the LHC Run-2
 - How to access their collection in the standard CMSSW event record
 - The electron/photon quantities used for typical selection and background rejection
 - Computation of selection efficiencies
 - Cut optimization and ROC curves
 - Use of electron/photon objects in CMS data analyses
 - Reconstruction of a Z boson mass peak from dielectron events (bonus)
 - A Z-> ee analysis exercise: reconstruction of Z from di-electrons. (bonus)

This page is mainly for planning and reference. It is okay to skim the day of.

> ## Facilitators CMSDAS LPC {{ site.year }}
> #### Lead Contact
> * [Chris Cosby](#facilitators), FNAL ([ccosby@fnal.gov](mailto:ccosby@fnal.gov))
>  
> #### All Facilitators
> * [Sweta Baradia](#facilitators), U.C. Davis ([sweta.baradia@cern.ch](mailto:sweta.baradia@cern.ch))
> * [Ruchi Chudasama](#facilitators), University of Alabama ([rchudasama@ua.edu](mailto:rchudasama@ua.edu)) 
> * [Grace Cummings](#facilitators), FNAL ([gcumming@fnal.gov](mailto:gcumming@fnal.gov)) 
{: .testimonial}


## Support


> ## Mattermost Chat
> **The [EGamma Short Exercise](https://mattermost.web.cern.ch/cmsdaslpc2025/channels/shortexegamma) channel will be available once you join the [CMSDAS@LPC2025](https://mattermost.web.cern.ch/cmsdaslpc2025/channels/town-square) team. 
{: .discussion}

### Previous editions:
 - [CMSDAS 2025](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2025ShortExEGamma)
 - [CMSDAS 2024](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2024EGammaShortExercise)
 - [CMSDAS 2023](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2023EGammaShortExercise)
 - [CMSDAS 2021](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2021EGammaExercise)
 - [CMSDAS 2020](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2020EGammaExercise)



> ## How to update this page (for facilitators):
> * Edit files in `_episodes/XX-Lesson.md`
> * Commit and push to the `gh-pages` branch
> * Check progress via the "Action" tab 
> * See rendered page
> * [Example CMSDAS lessons](https://kakwok.github.io/MDS_CMSDAS/index.html)
> * [Formatting reference](https://carpentries.github.io/lesson-example/04-formatting/index.html)
{: .callout}

{% include links.md %}

