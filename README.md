# Learning GitHub Advanced Security for Azure DevOps
This is the repository for the LinkedIn Learning course `Learning GitHub Advanced Security for Azure DevOps`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

Are you concerned about your application security? From third-party libraries to the code you write yourself, you need to know how to protect your application from attacks. If you're using GitHub to store and share your Azure development code, you're in luck. A whole new set of tools, GitHub Advanced Security for Azure DevOps, is here to simplify your administration and management. Join instructor Rob Bos in this course to learn about the variety of powerful scanning tools that can alert you to problems and opportunities through a manageable dashboard—completely integrated in your Azure pipelines.

_See the readme file in the main branch for updated instructions and information._

Files in this repos where specifically made for GitHub Advanced Security training purposes, for both on GitHub (GHAS) as well as Azure DevOps (GHAzDo). Here is a list of additions:
- Based on .NET core 5.0 to have vulnerable dependencies
- GitHub workflows with most recent action versions
- Pipeline definition for Azure DevOps
- Leaked secrets added to appSettings.Development.json

This results in GHAS/GHAzDo are that:
- Vulnerable dependencies are detected
- Code scanning detects vulnerability patters in the code
- Secrets are found in the repo

[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/learning-github-advanced-security-for-azure-devops
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D4D0DAQF_obeGgWur_Q/learning-public-crop_675_1200/0/1702946735119?e=2147483647&v=beta&t=hF7z75N6E1Anz2pHuhMwRK_pLy9qLkoPpyruxYawtU0
