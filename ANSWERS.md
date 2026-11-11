# Đáp án Final Project: Submission and Evaluation (Introduction to Git and GitHub - IBM)

Sinh viên: **Carwyn Nguyen (carwynetic)**  
Repository Part 1: [https://github.com/carwynetic/coursera3](https://github.com/carwynetic/coursera3)  
Repository Part 2 (Forked): [https://github.com/carwynetic/mcino-Introduction-to-Git-and-GitHub](https://github.com/carwynetic/mcino-Introduction-to-Git-and-GitHub)  
Pull Request Part 2: [https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pull/13489](https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pull/13489)

---

## Part 1: GitHub UI (12 points)

### Question 1 (4 points)
**Đề bài:** Task 1: Submit the public GitHub repository URL of README.md file, which contains the details about a simple interest calculator.  
**URL điền vào ô:**
```text
https://github.com/carwynetic/coursera3/blob/main/README.md
```

---

### Question 2 (2 points)
**Đề bài:** Task 2: Submit the public GitHub repository URL of Apache 2.0 license file named 'LICENSE' that contains the following topics: Definitions, Grant of Copyright License, Grant of Patent License, Redistribution, Submission of Contributions, Trademarks, Disclaimer of Warranty, Limitation of Liability, Accepting Warranty or Additional Liability.  
**URL điền vào ô:**
```text
https://github.com/carwynetic/coursera3/blob/main/LICENSE
```

---

### Question 3 (2 points)
**Đề bài:** Task 3: Submit the public GitHub repository URL of CODE_OF_CONDUCT file that contains the following content: Our Pledge, Our Standards, Enforcement Responsibilities, Scope, Enforcement, Enforcement Guidelines, and Attribution.  
**URL điền vào ô:**
```text
https://github.com/carwynetic/coursera3/blob/main/CODE_OF_CONDUCT.md
```

---

### Question 4 (2 points)
**Đề bài:** Task 4: Submit the public GitHub repository URL of CONTRIBUTING.md file that contains the following content: All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.  
**URL điền vào ô:**
```text
https://github.com/carwynetic/coursera3/blob/main/CONTRIBUTING.md
```

---

### Question 5 (2 points)
**Đề bài:** Task 5: Submit the public GitHub repository URL of the 'simple-interest.sh' file that contains the Bash script for a calculator to compute simple interest based on user input and the input fields like principal, rate of interest and time period.  
**URL điền vào ô:**
```text
https://github.com/carwynetic/coursera3/blob/main/simple-interest.sh
```

---

## Part 2: Git CLI (8 points)

### Question 6 (2 points)
**Đề bài:** Task 6: Copy and paste the curl command and its terminal output saved in the file named forked-repo, which shows your repository is forked from the repository 'ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub'.  
**Nội dung copy paste vào ô:**
*(Xem file `forked-repo`)*

```json
curl -s https://api.github.com/repos/carwynetic/mcino-Introduction-to-Git-and-GitHub
{
  "id": 1453388023,
  "node_id": "R_kgDOVqDw9w",
  "name": "mcino-Introduction-to-Git-and-GitHub",
  "full_name": "carwynetic/mcino-Introduction-to-Git-and-GitHub",
  "private": false,
  "owner": {
    "login": "carwynetic",
    "id": 217238012,
    "node_id": "U_kgDODPLJ_A",
    "avatar_url": "https://avatars.githubusercontent.com/u/217238012?v=4",
    "html_url": "https://github.com/carwynetic",
    "type": "User"
  },
  "html_url": "https://github.com/carwynetic/mcino-Introduction-to-Git-and-GitHub",
  "description": "Introduction-to-Git-and-GitHub",
  "fork": true,
  "url": "https://api.github.com/repos/carwynetic/mcino-Introduction-to-Git-and-GitHub",
  "default_branch": "main",
  "parent": {
    "id": 1050225087,
    "node_id": "R_kgDOPpkpvw",
    "name": "mcino-Introduction-to-Git-and-GitHub",
    "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "private": false,
    "owner": {
      "login": "ibm-developer-skills-network",
      "id": 70551872,
      "type": "Organization"
    },
    "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "fork": false
  },
  "source": {
    "id": 1050225087,
    "node_id": "R_kgDOPpkpvw",
    "name": "mcino-Introduction-to-Git-and-GitHub",
    "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "private": false,
    "owner": {
      "login": "ibm-developer-skills-network",
      "id": 70551872,
      "type": "Organization"
    },
    "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "fork": false
  }
}
```

---

### Question 7 (2 points)
**Đề bài:** Task 7: Copy and paste the terminal output of the first merge saved in the file named merge_branches, including the commands git checkout main and git merge bug-fix-typo. The output should clearly indicate that 1 file was changed.  
**Nội dung copy paste vào ô:**
*(Xem file `merge_branches`)*

```text
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
$ git merge bug-fix-typo
Updating ad95b0a..9f53c0a
Fast-forward
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
```

---

### Question 8 (2 points)
**Đề bài:** Task 8: Copy and paste the curl command and its terminal output saved in the file named bug-fix-revert, which verifies your pull request and shows the forked repository from which the pull request was created.  
**Nội dung copy paste vào ô:**
*(Xem file `bug-fix-revert`)*

```json
curl -s https://api.github.com/repos/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pulls/13489
{
  "url": "https://api.github.com/repos/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pulls/13489",
  "id": 5252088767,
  "node_id": "PR_kwDOPpkpv88AAAABOQyDvw",
  "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pull/13489",
  "number": 13489,
  "state": "open",
  "title": "Revert typo fix in README",
  "user": {
    "login": "carwynetic",
    "id": 217238012,
    "html_url": "https://github.com/carwynetic"
  },
  "body": "Revert the previous README copyright year change, restoring the original 2022 footer as required by the Git and GitHub exercise.",
  "head": {
    "label": "carwynetic:bug-fix-revert",
    "ref": "bug-fix-revert",
    "sha": "5896b2dcd6b408739aed4082a5e93ec490630389",
    "user": {
      "login": "carwynetic",
      "id": 217238012
    },
    "repo": {
      "id": 1453388023,
      "name": "mcino-Introduction-to-Git-and-GitHub",
      "full_name": "carwynetic/mcino-Introduction-to-Git-and-GitHub",
      "private": false,
      "owner": {
        "login": "carwynetic"
      },
      "html_url": "https://github.com/carwynetic/mcino-Introduction-to-Git-and-GitHub",
      "fork": true
    }
  },
  "base": {
    "label": "ibm-developer-skills-network:main",
    "ref": "main",
    "sha": "ad95b0abe521c61effc692e83d5babd5fbf25910",
    "user": {
      "login": "ibm-developer-skills-network"
    },
    "repo": {
      "name": "mcino-Introduction-to-Git-and-GitHub",
      "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
      "private": false,
      "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub"
    }
  }
}
```

---

### Question 9 (2 points)
**Đề bài:** Task 9: Copy and paste the terminal output saved in the file named github-branches, displaying the branch names and their status in the repository.  
**Nội dung copy paste vào ô:**
*(Xem file `github-branches`)*

```json
curl -s https://api.github.com/repos/carwynetic/mcino-Introduction-to-Git-and-GitHub/branches
[
  {
    "name": "bug-fix-revert",
    "commit": {
      "sha": "5896b2dcd6b408739aed4082a5e93ec490630389",
      "url": "https://api.github.com/repos/carwynetic/mcino-Introduction-to-Git-and-GitHub/commits/5896b2dcd6b408739aed4082a5e93ec490630389"
    },
    "protected": false
  },
  {
    "name": "bug-fix-typo",
    "commit": {
      "sha": "9f53c0a3629366cb37e8806d869d6e98dbe121b6",
      "url": "https://api.github.com/repos/carwynetic/mcino-Introduction-to-Git-and-GitHub/commits/9f53c0a3629366cb37e8806d869d6e98dbe121b6"
    },
    "protected": false
  },
  {
    "name": "main",
    "commit": {
      "sha": "9f53c0a3629366cb37e8806d869d6e98dbe121b6",
      "url": "https://api.github.com/repos/carwynetic/mcino-Introduction-to-Git-and-GitHub/commits/9f53c0a3629366cb37e8806d869d6e98dbe121b6"
    },
    "protected": false
  }
]
```

*(Hoặc định dạng terminal `git branch -a -v`:)*
```text
$ git branch -a -v
* bug-fix-revert                5896b2d Revert "Fix typo in footer year to 2023"
  bug-fix-typo                  9f53c0a Fix typo in footer year to 2023
  main                          9f53c0a Fix typo in footer year to 2023
  remotes/origin/HEAD           -> origin/main
  remotes/origin/bug-fix-revert 5896b2d Revert "Fix typo in footer year to 2023"
  remotes/origin/bug-fix-typo   9f53c0a Fix typo in footer year to 2023
  remotes/origin/main           9f53c0a Fix typo in footer year to 2023
```
