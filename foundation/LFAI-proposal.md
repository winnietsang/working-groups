== ONNX Project Proposal

*Name of the project*: ONNX (Open Neural Network eXchange)

*Requested maturity level*: Graduated

*Description*

ONNX is an open format to represent deep learning models that execute on a variety of hardware platforms and clouds, which can be optimized for ONNX.  ONNX allows AI developers to more easily move AI models between tools that are part of trusted AI/ML/DL workflows.  The ONNX community was established in 2017 by Facebook and Microsoft to create an open ecosystem for interchangeable models.  Support for ONNX has grown to over 30 organizations.   The most recent ONNX community meeting had over 150 attendees in Santa Clara, CA.  The upcoming community meeting at Microsoft Shanghai on November 18this capped at 100 attendees and will blend both the most active community contributors with a healthy number of new organizations and contributors ready to join the community and start contributing.
ONNX is a mature project with 138 contributors, over 7K stars and over 1K forks and with a steady stream of ongoing commits.  ONNX is used by and has active contributors from Microsoft, Facebook, Amazon, Intel, Nvidia, Qualcomm, Apple, Uber, IBM (e.g., Z mainframe, P Power systems, I Intel systems, etc. as well as new hardware architectures under development).  ONNX is being adopted by numerous startups with edge and IoT devices – which of interest to LF Edge and LF Energy. 
ONNX is already being used in LFAI (Linux Foundation – Artificial Intelligence Foundation) projects.  LFAI and ONNX values are strongly aligned:  Open, welcoming and respectful, transparent and accessible, merit, speed.  ONNX community is large and growing and LFAI can help education and onboard more ONNX users, as well as grow the community of contributors and capabilities.  

*Possible integrations with existing LF DL projects:*

Acumos: https://docs.acumos.org/en/boreas/submodules/on-boarding/docs/onboarding-ONNX-PFA-guide.html
Adlik: https://github.com/Adlik/Adlik
Angel: https://github.com/Angel-ML/angel

*License*: MIT

*Source control*: https://github.com/onnx/onnx

*External dependencies*:

Depends on:



Includes code from:



*Initial committers:*

ONNX Steering Committee, Initial Committers, and Contributors:
Steering Committee - Announcement message to community: https://github.com/onnx/onnx/wiki/Expanded-ONNX-Steering-Committee-Announced!
•	Prasanth Pulavarthi (Microsoft)
•	Joe Spisak (Facebook)
•	Vin Sharma (Amazon)
•	Harry Kim (Intel)
•	Dilip Sequeira (Nvidia)
Committers and Contributors:

*Infrastructure requests:*
In order to facilitate external development, we need to make it easy for anyone to run integration
tests. Currently, we’re using Travis CI for integration tests which provides CPU tests only. There has
been a number of issues where only GPU components failed, while CPU tests were passing.
This forces developers to run integration tests on GPU boxes manually.
We’d like to make use of LF continuous integration environment and request a GPU support.
Since AWS is planning to be involved in the project, we should discuss the potential of running
the integration tests on AWS GPUs.

*Current mailing lists:*
None, we will request LF to create lists for users, developers, and TSC.

*Resources:*

  *	CI - https://travis-ci.org/onnx/onnx/
  *	Issue tracker - https://github.com/onnx/onnx/issues
  *	DockerHub - https://github.com/onnx/onnx-docker 
  *	PyPI - https://pypi.org/project/onnx/

*Website:*
The website is at https://onnx.ai and aliases onnx.github.io which serves content from https://github.com/onnx/onnx.github.io/.
Microsoft has sponsored a website refresh which is will go live in November.

*Release methodology & mechanics:*
The release is performed according to community agreed process: https://github.com/onnx/onnx/blob/master/RELEASE-MANAGEMENT.md

*Social media accounts:*
https://twitter.com/onnxai
https://facebook.com/onnxai

*Existing sponsorship:*
Microsoft, Facebook, Intel, NVIDIA, Amazon, IBM, Qualcomm, NVIDIA, Apple are some of the active contributors to repositories in the ONNX  Github organization.
Alibaba, AMD, ARM, AWS, Baidu, BITMAIN, CEVA, Facebook, Graphcore, Habana, HP, Huawei, IBM, Idein, Intel, Mathworks, Mediatek, Microsoft, Neural Network Libraries, NII, Nvidia, NXP, Oath, Preferred Networks, Qualcom, SAS, Skymizer, Synopsys, Tencent, Unity.


*CII Best Practices Badge:*