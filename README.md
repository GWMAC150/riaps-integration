[![Build Status](https://travis-ci.com/RIAPS/riaps-integration.svg?token=pyUEeBLkG7FqiYPhyfxp&branch=master)](https://travis-ci.com/RIAPS/riaps-integration)

# riaps-integration

In order to use the integration scripts and setup your environment correctly you will need to download a number of other packages from the RIAPS organization. At the time of these instructions, RIAPS is a private organization and you need to have atleast read-level access to the repositories. To get this access please contact Prof. Gabor Karsai or Prof. Abhishek Dubey.

Once you get the read level access you need to set up an OAUTH Token.  Read https://developer.github.com/v3/oauth/. Create a a personal access token as discussed on the page. Set the SCOPE to "repo". That will grant the token access to "Grants read/write access to code, commit statuses, invitations, collaborators, adding team memberships, and deployment statuses for public and private repositories and organizations."

Once you have the token you must use it everytime you want to download the new release in your machine. A trick is to create an environment variable GITHUB_OAUTH_TOKEN with the token value in your bash profile.

