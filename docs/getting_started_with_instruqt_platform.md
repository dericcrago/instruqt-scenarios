## Basic steps to create a track on Instruct platform
 
- Navigate to https://play.instruqt.com/redhat/tracks/wizard
- Click `Next` and provide track Title, Slug (URL which identifies your track), Teaser (description of your track) and Description.
- Select the Environment (Docker Container or Virtual Machine) where the sandbox environment will be created and to run track challenges.
  - In case of Virtual Machine, enter a VM name, Google Cloud image for use of virtual machine and Virtual Machine Type.
  - In case of Docker, enter the docker image URL.
  - Click `Next`.
- Fill the details (title, slug, teaser, assignment details) of the first challenge and click `Next`.
- Enter the information about the challenge in *Notes* section and that'll be displayed while the environment is being started and click `Next`.
- Define the tabs of the challenge and then click `Finish`.

## Things to remember while creating a track on Instruqt
 
- Insruqt platform uses images from Google Cloud for track challenges.
- Use [`instruqt` CLI tool](https://docs.instruqt.com/building-tracks/software-development-kit-sdk) to edit, modify and delete changes on Instruqt platform.
