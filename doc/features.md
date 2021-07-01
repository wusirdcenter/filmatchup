## Functionality and Features

### 



![](../img/features.png)



The features are as follows.



| Number |           Module           | Features                                                     | Notes |
| ------ | :------------------------: | :----------------------------------------------------------- | ----- |
| 1      |        User module         | (1)  User login <br />(2)  Real-name authentication <br />(3)  Third-party account binding <br />(4)  AccessKey/AccessSecret generation ( indirect access to lotus node) <br />(5)  Roles management (user with different role owns different pages)<br /> |       |
| 2      |   DataCap  distribution    | (1)  Apply to notaries to receive DataCap (include show the reputation scores at present, allocation policy, service contract,  etc.)<br />(2) Audit request from clients manually <br />(3)  DataCap allocation policy  setting  and auto approved <br />(4)  DataCap allocation list: when/who/How much <br /> |       |
| 3      |       Bidding module       | (1)  client -- Bid Invitation management:  list,create, delete, modify, publish, cancel <br />(2)  miner -- Bidding management : list, modify,cancel            (3)  bids status display: published, finished, aborted,   discarded<br />(4)  After the transaction, client and miner will give review and score to each other. (Including default review strategy, etc.)                                                                                                                                                              (5) After the transaction, complaints can be made against rule-violating acts by listing up evidences.  <br> |       |
| 4      |  Auto matching-up policy   | (1)   Policy for client  <br />       - miner blacklist <br />       - miner candidate's  reputation scores  <br />       - miner candidate's   max price <br />       - miner candidate's  regions  <br />       - miner candidate's  longest completion time  <br />(2)  Policy for miner <br />       - client's  reputation scores in the bid<br />       - client's  min price in the bid  <br />       - client's  region  in the bid  <br />       - client's shortest  completion time   in the bid <br />(3)  Priority configuration：clients are able to configure the  priority  of selection conditions <br />(4)  The system's default policy <br />       -  If there are multiple miner candidates in the shortlist,  the new miner will be the first choice.  <br /> |       |
| 5      |     Execution  module      | (1)   Manual execution  <br /> (2)   Auto execution  configuration <br /> |       |
| 6      |     Reputation module      | A basic reputation system based on real-name authentication, third-party account binding, miners' computing power, miners' fault conditions, mutual evaluation between transaction parties, and registration time |       |
| 7      |   Communication channel    | (1) Announcement display<br />(2) User message               |       |
| 8      | Operations and managements | (1) Announcement management<br />(2) Message List <br />(3) reputation policy management<br />(4) Complaints  management <br />(4) System parameters  configuration<br /> |       |


