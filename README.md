![SciOly API](https://user-images.githubusercontent.com/65052071/116440264-ebdf6d80-a815-11eb-8616-276a29558474.png)

![Uptime](https://img.shields.io/uptimerobot/ratio/7/m787980980-78325a4e551f1aad9a2d3911?color=2E66B6&label=Uptime&style=flat-square) ![Pull Requests](https://img.shields.io/github/issues-pr-raw/aakhilv/scioly?color=2E66B6&label=Pull%20Requests&style=flat-square) ![Contributors](https://img.shields.io/github/contributors/aakhilv/scioly?color=2E66B6&label=Contributors&style=flat-square) ![Commits](https://img.shields.io/github/commit-activity/m/aakhilv/scioly?color=2E66B6&label=Commits&style=flat-square)

This is a community run Science Olympiad api. We are not affiliated nor endorsed by [Science Olympiad Inc.](https://www.soinc.org) in any way.

---

## Adding a problem to the database

### Step 1

Fork the [aakhilv/scioly](https://github.com/aakhilv/scioly/fork) master branch if you haven't already.

### Step 2

Add your problem to the [db.json](https://github.com/aakhilv/scioly/blob/main/db.json) file with the following format:

```json
{
  "category": "Specify the category here",
  "problem": "Insert question here?",
  "answer": "Insert answer here.",
  "image": "https://example.com/image.png",
  "choices": ["A", "B", "C", "D"]
}
```

* Only include the `image` key if the problem you are submitting has an associating image.
* If the problem is to be a to be a free/written response, do not include the `choices` key. If the problem is to be a true or false answer, only put two items in the array as `["true", "false"]`. If the problem is to be a multiple choice answer, include two or more items in the array.

### Step 3

Submit a [pull request](https://github.com/aakhilv/scioly/compare) from your fork's master branch to this repo's master branch.

### Step 4

Once accepted, your problem will start showing up in the [api](https://scioly.js.org/api) within a few hours. Additionally, please make sure to check the pull request every so often in case we require any changes from your end.

---

## Category codes

|Category|Code|
|---|---|
|Anatomy and Physiology|`anap`|

---

## Terms of Service

§ 1 Principles
JS.ORG is a free service provided by the owner of JS.ORG as stated in the imprint. The service will be only called "JS.ORG". All services are incumbent upon these terms and conditions.
JS.ORG accompanies and extends the service "GitHub Pages" provided by GitHub, Inc ("GitHub"). JS.ORG provides free subdomains underneath the domain "js.org" to be used as a custom URL for a GitHub Page.
The Terms of the GitHub service and all rights of GitHub, Inc remain unaffected by the terms of JS.ORG.
Communication between JS.ORG and the user will take place on GitHub in the form of issues, pull requests or comments.
By submitting a pull request in the GitHub repo that accompanies and hosts JS.ORG with the wish to add a record to the list of domains, the user attends the JS.ORG service and accepts the terms and conditions as the sole basis of all services provided by JS.ORG.
§ 2 Availability and reservations
JS.ORG aims to ensure the constant availability of the subdomain service. A right on constant availability does not exist. All services in connection with this free service will be provided on a voluntary basis. The user acquires no ownership or other rights to single services, the registered subdomains and the whole service.

If the user violates the terms, JS.ORG is entitled to exclude the user from the service without notice subjected to damages and other claims. JS.ORG is entitled to terminate or modify the service at any time without notice and without explanation. In that case the user of JS.ORG will be informed timely, at least 7 days in advance by JS.ORG. The relevant information about the impending use and deletion is shown simultaneously to the concerned users.

§ 3 Termination
Both sides can terminate at any time without stating any reasons.
The user cancels the service by removing the CNAME file in their repository and making a pull request in the repository of JS.ORG with the wish to remove their subdomain from the list of active JS.ORG domains.
JS.ORG may also terminate the provision of a certain or all subdomains. Concerned users will be notified at least 7 days in advance by an issue in their GitHub repository
§ 4 Rights and Duties of the user
A transfer of a GitHub Page together with its JS.ORG subdomain is allowed as long as the new users accepts these terms and conditions, in particular § 2 of the terms (no property right). The user receives a non-exclusive right from JS.ORG to use the service. The use permit expires with cancellation of the conctractual agreement.

The user is fully responsible for the content provided by its GitHub Page, and is also responsible to extricate JS.ORG from all third party claims. The user warrants not to transmit any material that violates the rights of others or violates statutory provisions.

In particular providing content like the following is prohibited:

Piracy (warez, videos, MP3s, DVDs, software, etc.)
Phishing, scam, malware, viruses
Copyright offense
Dubious business models (eg, pyramid schemes, chain letters, etc.)
Content that is unlawful, obscene, threatening, abusive, libelous, or scandalous
Content which led to committing criminal acts or acts that undermine the civil order, or otherwise contrary to national or international laws
Pornography or content intended for adults only
Unsecured Web 2.0 platforms (eg. no captcha protection in forums, blogs, guest books)
File or Image hosting
Sites with other illegal content
A violation of these rules will result in immediate deletion of the JS.ORG domain.

The user is obliged to publish legals on his website which contains at least the full name, mailing address and an e-mail adress.

§ 5 Limitation of Liability
In principle JS.ORG takes no responsability for the support. The use of the provided services of JS.ORG takes place at your own risk. This refers in particular to the functionality, availability and freedom from viruses of the provided services as well as damage caused by the use of programs, program components and scripts/applets. The user is obliged to create local copies of all his data at JS.ORG for security reasons and regularly to secure all stored data. JS.ORG indicates that JS.ORG is a free service and does not create data backups for the users.
The user is liable for any use of the service performed by his GitHub user account. Legal representatives are liable for minors. The user therefore has to ensure that his access can not be misused by third parties.
JS.ORG provides the service without any express or implied warranties. JS.ORG is not liable for inadvertent disclosure, damage or loss of transmitted, received or stored data from JS.ORG. The user expressly acknowledges that these terms also effect third party supplies.
For the purposed service usage as described above JS.ORG solely assume the liability for the injury to life, limb and health, and other damages caused by gross neglect of duty on JS.ORG
A liability of JS.ORG for slight negligence exists only for breach of an essential contractual obligation
A liability of JS.ORG for further damages, in particular consequential damages, indirect damages or lost profits is excluded.
A liability for malfunctions or failure as well as unauthorized access from outside the sphere of influence of JS.ORG is only in the context of intent and gross negligence.
§ 6 Name of the subdomain
Each user can select the names of subdomains in accordance to the URL provided by the GitHub Pages service and with respect to a public available list of restricted names published in the JS.ORG repository. It is sole responsibility of the user to consider whether the name is contrary to statutory provisions, third party rights (including trade marks or registered rights), or morality. If this is the case, the registration of the subdomain is to be omitted. The same applies to subdomains, whose name is misleading, or suspect websites which are excluded of the participation in the service because of their content according to § 4.

§ 7 Absolute ban of spam
References to domains registered at JS.ORG in unsolicited commercial e-mail or similar media (spam) are not allowed. The mass registering of domains for the purpose of irritation to the users of search engines are also considered spam and are also inadmissible.

§ 8 Manipulation
It is prohibited to auto retrieve masses of JS.ORG subdomains.

§ 9 Responsibility
JS.ORG is not responsible for the names of subdomains or the content of external websites that are registered as link destinations of subdomains, or otherwise linked to this service.

§ 10 Place of jurisdiction
Service provision and the usage of the service according to these terms and conditions is exclusively subject to the application of the law of the Federal Republic of Germany. Application of conflict of laws of private international law is expressly excluded.

The place of jurisdiction for JS.ORG is Munich, the residence of the owner of JS.ORG as stated in the legals.

For disputes with users who are defined as contractors after §14 BGB, Munich is agreed as place of jurisdiction. For users who do not have general jurisdiction and no resident in Germany at the time of the commencement of proceedings, Munich will be the place of jurisdiction.

For users, who are consumers within the meaning. § 13 BGB, the general jurisdiction of the domicile will remain in Munich.

§ 11 Change of Terms
JS.ORG reserves the right to make changes to the Terms of Service. The user will be informed by JS.ORG of the changes through a notice in the readme section of the JS.ORG repository.

§ 12 Severability clause
If single clauses of these terms and conditions are fully or partially invalid or void, respectively will be, so otherwise the validity of these terms and conditions remains untouched.
