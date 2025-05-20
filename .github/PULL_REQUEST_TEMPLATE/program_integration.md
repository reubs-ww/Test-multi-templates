# what's this about?
[TCX-](https://kaligo.atlassian.net/browse/TCX-)

# design



# caveats



# impact
<!-- Does this PR have changes which rely on the credit internal_information?
Check if we need to reload the attributes in the sender and if it will affect bonus credit -->


# test cases
Create a new sheet to track integration UAT/PVT results based on the below
[baseline test case](https://docs.google.com/spreadsheets/d/1fdC2ORWBOZAi8FBdTrH_HTiCy2OudPniJuVG6jCCld8/edit?gid=1468307557#gid=1468307557)



# notes
For new sender and receiver, please update this [notion page](https://www.notion.so/kaligo/API-Loyalty-Programs-Reprocessable-a2374a0620b94daab6aa466cf1800112)

# integration checklist
- [ ] secrets deployed? [example](https://github.com/Kaligo/devops/pull/9228)
- [ ] whitelisted endpoints? [example](https://github.com/Kaligo/devops/pull/9499)
- [ ] whitelist custom ports? 
  - [example](https://github.com/Kaligo/devops/pull/8151)
  - [example](https://github.com/Kaligo/devops/pull/9497)
- [ ] Fidelity updates? [example](https://github.com/Kaligo/fidelity/pull/72)
- [ ] UAT json data done? [example](https://github.com/Kaligo/transfer_connect/pull/4241)
- [ ] Operational information added?
  ```json
  { "credit": {
    "safe_to_reprocess": { "base": true, "bonus": true },
    "flag_duplicate_as_success": { "base": true, "bonus": true }
    },
    "error_mappings": {
      "safe_to_reprocess": []
    }
  }
  ```
- [ ] Promotion config added?
  - [tracking sheet](https://docs.google.com/spreadsheets/d/1_ImougipiX7l1AEGHXkFao9liYzrCyC1POG3NotMheU/edit?gid=684298734#gid=684298734)
- [ ] Appendix 2 updates
- [ ] Appendix 4a updates
- [ ] Auth configs set up?
