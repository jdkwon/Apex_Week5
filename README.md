# Project 5 - Encryption

Time spent: **6** hours spent in total

## User Stories

The following **required** functionality is completed:

1\. Symmetric Encrypt/Decrypt
  * [X]  Required: Repair the symmetric encrypt and decrypt code

2\. Encrypted Message 1
  * [X]  Required: Decrypt the government message
  * [X]  Required: Encrypt a response and include in this README
  > UduN5kOnzMQO/PfuUui+QL+LuHmAu3dp46HpglZ2rmkVlzM8HRMqqlqLmfgYNsGV

3\. Generate Public-Private Keys
  * [X]  Required: Repair the key generator code
  * [X]  Required: Generate keys for "johnsteed" and add him to the Agent Directory

4\. Asymmetric Encrypt/Decrypt
  * [X]  Required: Repair the asymmetric encrypt and decrypt code

5\. Create/Verify Signature
  * [X]  Required: Repair the create and verify signature code
  
6\. Encrypted Message 2
  * [X]  Required: Decrypt the message
  * [X]  Required: Verify the message
  * [X]  Required: Include a response message in this README
  * [X]  RESPONSE:
  > Message:
  > voK8KVtfidh2gQAuY4L93vTs9cyFuDdJ6ihfxPoPGOFRQh8ohT6K0dKJ7NKe8Uc/1v+b9Q7uWlK6XZyTaV3KND8ORlTBCMsvXSHH9PNQcmdthRoktQDZaP/kqEk1aEjD55EYXxjt07q4EMnSpeV6iknVznniY+yT/U8fqszXMDpBL/BH8QhuSL11DtrjxngATGJNqWmUA7y2/dnS0vIizh9o5hTq1TBNhnnp1bITM0lFihMoRGkOKhWAxRt5s6wu3sx4KM0RKw6c9XJhda4tvfAWV5V3HgW60hMVu6O3lsm/iarqd4rSztsPcC8umQhKz00DuvpxRdLb+yS67YOuTA==

  ---

  > Signature:
  > IadBaN+orGO9lit2EO6PaAiUhY4UxCua1R05DNXO1vKpdufDkHf1iiH/Y6Kqf2znuzxtlKCXRcWIICMWpSWRw45f0aNHtcdPBuUKgV81j2rS42pjdUNW9pqpT1vsIcMHazaqC0mb8P4HCPr2ghPiRUJUyuOB0Zt6+FsnNknEnZjFnbKn1Rc6KvJcpFaWnTJ31VHvIwBO1IJPgMQvxDVoIAiRG4KBMJVaKGokBo7t8bFnoWrmCHab2ZJO2FL7HnJ65cy8nnfl4FUAmADPqh+4uylEbE0nMdGncrIKBIrATXvlkM4gkTShdJIKOa564dxwD+0NTq4jbzuovyBoeae57Q==

7\. Agent Messages
  * [X]  Required: Repair the dropbox code
  * [X]  Required: Repair the messages area
  * [X]  Required: Display encrypted messages for all agents
  * [X]  Required: Messages indicate whether the message signature is valid
  * [X]  Required: Your messages are automatically decrypted

8\. Identify the Double Agent
  * [X]  Required: Decrypt as many email messages as possible

  > Email 1: The SQL injection we discussed is in place. Just search for an agent.
  
  > Email 2: N/A
  
  > Email 3: Today I was able to sneak several XSS vulnerabilities onto one of the encrypt/decrypt pages.
  
  > Email 4: N/A
  
  > Email 5: Let me know before you go inside. I'll create a distraction. - Austin
  
  > Email 6: Let me know before you go inside. I'll create a distraction. - Natasha
  
  * [X]  Required: Identify the double agent: **Natasha**


The following objectives are **optional**:

* Bonus Objective 1\.
  * [ ]  Track down the bugs in the code and fix them.

* Bonus Objective 2\.
  * [ ]  Write a report of your discoveries (longer than 300 characters).
  * [ ]  Compose a secure email for sending over an insecure network.
  * [ ]  Include the email with your encrypted report in this README.

* Bonus Objective 3\.
  * [ ]  Add a "Create/Verify Checksum" section to the Encryption Tools area.

* Advanced Objective 1\.
  * [ ]  Add support for other symmetric algorithms.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/C0QbtUm.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

It was not too bad. The most difficult thing was figuring out What to tell to the Agent to let him/her know about the new secret name.

## License

    Copyright [2017] [James Doohyun Kwon]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
