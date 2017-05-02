# Setting Up a USSD Service for MicroFinance Institutions
#### A step-by-step guide

- Setting up the logic for USSD is easy with the [Africa's Talking API](docs.africastalking.com/ussd). This is a guide to how to use the code provided on this [repository](https://github.com/Piusdan/AT_WORKSHOP) to create a USSD that allows users to get registered and then access a menu of the following services:

| USSD APP Features                            |
| --------------------------------------------:| 
| Request to get a call from support           | 
| Deposit Money to user's account              |   
| Withdraw money from users account            |   
| Send money from users account to another     |   
| Repay loan                                   |   
| Buy Airtime                                  |  

# WORKSHOP's WORKFLOW
This workshop will use Github to manage the whole workflow. We mainly make use of *Github issues*, *branching*, *pull requests (PR)* and *reviews*.


### Workflow:

- Fork [this](https://github.com/JKUATSCOSIT/AT_WORKSHOP) repository to your Github profile
- For the workshop create a branch thus:
  
  ```
  <username>-language-framework>
  e.g.
  PiusDan-python-flask for the python-flask version of the app.
  ```
- Your solutions should be put in a folder named `language-framework` e.g. `python-flask`
- Work out your solution from the branch, then commit changes and push.
- Raise a PR against your `master` branch (not this project's master branch).
- Your PR will then be reviewed by the AT team and merged appropriately

See example [here](https://github.com/ProfNandaa/upskilling-c-sharp/pull/1)


## Appendix

### Workflow Explained

Quick Git walkthrough:

- Fork the repo (click on the "Fork" button at the top-right).
- Clone your forked repo, e.g.
  
  ```
  git clone git@github.com:JKUATSCOSIT/AT_WORKSHOP.git
  ```
- Create a branch for your solution, e.g.
  
  ```
  git checkout -b PiusDan-python-flask
  ```
- After making changes, stage the changes:
  
  ```
  git add --all
  ```
- Commit the staged changes, e.g.
  
  ```
  git commit -m ""Flask app working!
  ```
- Push your changes, e.g.

  ```
  git push origin at-workshop
  ```

**Making A pull request:**

**NOTE:** Make sure you choose your `master` branch as the _base_, and not the original repo's master branch.

<img width="1072" alt="screen shot 2017-02-10 at 10 25 15 am" src="https://cloud.githubusercontent.com/assets/10922198/25618477/c37bf9d2-2f4f-11e7-8903-44e5ff57c4fc.PNG">

**Reviewing Code:**
Your mentor will review your code and give you feedback on what to improve on. If all looks good, they will merge your PR once your submission _meets expectations_.

<img width="1063" alt="screen shot 2017-02-10 at 10 26 10 am" src="https://cloud.githubusercontent.com/assets/10922198/25618617/5b33f252-2f50-11e7-9f02-f748f8ac05c1.png">

