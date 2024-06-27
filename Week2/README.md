## Task 1

### Task 1.A

**- What does the "Not Secure" warning mean in the first picture and what risks does visiting sites with the warning pose?**

The "Not Secure" notice denotes a connection to that page that is not secure. You are being warned that the information provided and received over that page is not secure and might potentially be taken or altered by intruders, hackers, or organizations having access to the Internet's infrastructure, such as governments and Internet Service Providers (ISPs). It means that a secure HTTPS connection has not been used and the connection between the browser and the website is not secured or encrypted. 

The risks are that personal data and credentials can be intercepted or viewed by intruders, the data can be modified, phishing attacks using fake versions of the website that users tend to enter sensitive data and it's recommended not to proceed with online purchases through theses "Not Secure" sites. 
  
**- Why does the second site show up as "trusted" to the browser?**

The second website's appearance as "trusted" suggests that the connection between your browser and the website server is secured using HTTPS. The implementation of HTTPS by a website makes it far more difficult for intruders to intercept or tamper with data as it is transmitted between your device and the website's server.
The "trusted" websites have active SSL/TLS certificates which are issued by trusted Certificate Authorities (CAs). The SSL/TLS certificate enables encryption between the server and the user's browser. It authenticates the website by checking the signature of the CA in the certificate when the user accesses the site. The SSL/TLS certificate also ensures the integrity of the data transmission. 

**- What other ways are there to detect a phishing/scam site?**

Few of the other ways to detect phishing/scam sites are:
- Checking the website's URL for any indications of shady domains or typos such as by adding extra letters or using a domain that is not affiliated with the legitimate company.
- Checking to determine if the website's domain name corresponds to the official domain of the claimed organization. 
- Phishing websites may have poor design, typos, or grammatical problems.
- When opening links in emails from unknown senders, verify the sender's identity.
- Looking for contact information such as email, phone number, and physical address.
- Using an antivirus software.

Tools: 

- Domain ownership & registration details
  - WHOIS lookup
- Phishing detection
  - McAfee SiteAdvisor
  - Norton Safe Web
  - Google Safe Browsing
  - Avanan
  - Barracuda Sentinel
  - BrandShield
  - Cofense PDR
  - RSA FraudAction
  - IRONSCALES
  - KnowBe4
  - Mimeset
  - Microsoft Defender
  - Vailmail

Reference: https://www.csoonline.com/article/569867/9-top-anti-phishing-tools-and-services.html

**- What is typosquatting and how does it relate to the pictures?**

Typosquatting is a type of attack where fraudulent domain names are created to exploit common typing errors made by users and then to users to visit a fraudulent site instead of a legitimate website. The intention can be stealing personal data, distributing malware, or phishing. 

In picture 1, there's a typo in danskebank[k].fi and it appears as a "Not Secure" site in the address bar. it is a typing error. 
The second picture shows as "trusted" browser but the bank's official website does not appear to be ```danskebank.io```. Therefore this is also an error made by the user. 
![image](https://github.com/SecurityEngineering-2023/security-engineering-submissions-PiyumiUoR/assets/53691448/829b3e92-1a86-4580-8b83-2d4dc3a4b577)

The third picture shows that the website is "trusted" and also it's legitimate w.r.t. the official website details. 

  **- What is UDRP and how does it help with combatting typosquatting?**

The Uniform Domain Name Dispute Resolution Policy (the UDRP Policy) outlines the legal framework for resolving disputes between a domain name registrant and a third party (i.e., a party other than the registrar) regarding the unauthorized registration and use of an Internet domain name in the generic top-level domains (gTLDs) such as .biz,.com,.info,.mobi,.name,.net, org and also the country code top-level domain that has voluntarily adopted to the UDPR policy and is established by ICANN (Internet Corporation for Assigned Names and Numbers). 

The mechanism is giving trademark owners a way to settle disputes over domain names that are confusingly comparable to or infringing on their rights. This includes cases of typosquatting, in which domain names containing slight misspellings or variations of well-known trademarks are purposefully registered.

If such a case is occurred the trademark owners can file a complaint to the UDPR against the infringing domain and seek for a cancellation or transfer. The UDPR reviews the case and makes decisions based on the intellectual property law and the domain name matters. 

  **- If you were to own the domain [ouspg.org] and would be running your crypto banking application at [bank.ouspg.org], what domains could you monitor for warning signs of possible phishing attempts against your customers?**

Monitoring for potential client phishing attempts is essential for ensuring the security and reliability of the crypto banking application. The domains that are similar to **ouspg.org** or that are strongly connected to **bank.ouspg.org** should be monitored in order to accomplish this. 
Continually tracking such variations and taking action against suspect URLs will help in preventing phishing attacks against consumers and uphold the integrity of the crypto banking application. To automate and streamline this process, you could also think about engaging with cybersecurity experts and utilizing domain monitoring tools and services.

Sample domains that we can monitor for the possible phishing attacks are:
  - bank.ouspg.net
  - bank.ouspg.app
  - bank.ouspg.cc
  - bannk.ouspg-crypto.com
  - ouspgcrypto.login.org
  - bank.0uspg.org
  - secure.bank-ouspg.org
  - bank.ouspgapp.org
  - 0uspg.org
  - bɑnk.ouspg.org
  - bnak.ouspg.org
  - ousgp.org
  - bannk.ouspg.org
  - bank-ouspg.org

Using a domain monitoring service can alert the owner of possible malicious domains. The customers should be warned and advised to use HTTPS which is a secure connection when engaging with the bank. 

### Task 1.B

**- What are digital certificates used for?**

Digital certificates are used for, 
 - To verify the identity and to authenticate components involed in a transaction.
 - The access to the data can be controlled.
 - The authorization can be done using the digital certification.
 - The transmit data is encrypted when usind a certificate.
 - Electronic signatures are created for documents and transactions. 
 - The relaibility of the transmission is increased and evetually the man-in-the-middle attacks are prevented.
 - Email security can be increased using encryption.
   
    **- Why are certificates important for online payments and banking security?**
        - To ensure the trust of the user. After the digital certificate authenticates the website the user can see the padlock sign or the 'https' in the address bar.
        - The encryption feature of the digital certificate makes the communication between the user and the server encrypted and then it is protected. This also helps to keep the data unaltered in between the transaction.
        - For the online transactions, this serves a huge role and to prevent phishing attacks by providing indicators.
        - Financial institutes need to use certificates as for the compliance.
        - Digital certificates are used to secure the mobile apps.
   
    **- What other uses do certificates have?**
        - Certificates are used to establish secure VPN connections.
        - Educational institutes secure learning platforms, use to authenticate students, and provide secure VPN connections to certain platforms.
        - Govvernment uses the certificate to online services, digital signatures and to establish secure communications with citizens.

**- What kind of attacks does TLS mitigate and why is this important for online banking?**
- The TLS encrypts the data transmission and prevent eavesdropping. The sensitive data can be protected.
- Data encryption also prevents the Man-in-the-Middle attacks and eventually fraudulent transaction, unauthorized access and theft. 
- The user's device is protected by preventing accepting the tampered data.
- TLS also helps to identify fake websites and provide trust to users to enter their sensitive data.
- TLS also prevent session hijacking and session fixation during a online banking session.

## Task 2

**Questions: Payments**

**- Why do modern payment cards use a chip and not a magnetic stripe?**

The main two reasons are improved security (with associated fraud reduction), and the possibility for finer control of "offline" credit-card transaction approvals. 
Since magnetic stripe data is easily reproduced and duplicated, fraudsters can quickly produce fake cards using stolen data. Because EMV chip cards generate distinct cryptographic algorithms for each spending, making any stolen data useless for later transactions, they are significantly more resistant to being copied.
In some cases, the card terminal where you make a payment may not have an immediate or stable internet connection to communicate with the card issuer's authorization system in real-time. They can program the chip with specific rules and limits that dictate when an offline transaction is approved or declined. These rules can be more fine-tuned and customized to suit the issuer's risk tolerance and the cardholder's preferences. Even for offline transactions, data is stored in the chip and can be uploaded to the issuer's system when the card is used in a terminal with an internet connection. 

**- What are EMV Certificates and why are they relevant for payment protection?**

Payment card issuers receive digital certificates from the EMV Certificate Authority[28]. The payment card chip gives the terminal the card issuer's public key certificate and SSAD upon request. In order to confirm trust for the CA and, if trusted, to ensure the public key of the card issuer was signed by the CA, the terminal gets the CA's public key from local storage. The terminal utilizes the card issuer's public key to confirm the card's SSAD was signed by the card issuer if the card issuer's public key is legitimate.

**- What attacks exist against payment cards?**
    - Card-not-present?

    A card-not-present transaction (CNP, mail order/telephone order, MO/TO) occurs when the cardholder is unable or unwilling to present the card for a merchant's visual inspection at the time an order is placed and payment is processed. It is most frequently utilized for online payments. Merchant banking systems provide easy ways to check this information, which is a popular preventive step for merchants who only let shipment to addresses permitted by the cardholder.


    - Contactless payment?

Although contactless payments are quicker, they are normally only used for low value purchases because no signature or PIN verification is usually required. Due to a lack of authentication, fraudulent purchases can be conducted while the cardholder is unaware that their card has been lost. 

    - Lost or Stolen

  A stolen card can be used for transactions until it is reported. 

    - Phishing

  The cardholder can be tricked into providing the card details to a phishing email or to a fake website. 

**Questions: MFA**

**- How is multi-factor authentication (MFA) used in banking?**

MFA needs the user to provide multiple authentication factors to verify the user's identity before handling any sensitive information. 
The authentication factors are: 
- Something the user has: Any physical object in the possession of the user: OTP sent to the mobile phone, bank card
- Something the user knows: Certain knowledge only known to the user: username, password, PIN, security questions
- Something the user is: Some physical characteristics of the user (biometrics): a fingerprint, face identification, behavioral analytics

**- How does multi-factor authentication increase payment security?**

MFA allows stronger authentication using different categories as mentioned above in MFA factors. The risk is reduced due to the fact that attackers need additional authentication factors to gain access. Even if the credential is leaked somehow, the access is avoided. 
Using a separate channel to send OTPs is used as compromising one channel does not necessarily compromise the other. If the intruder manages to gain the OTP, since the validity period of the OTP is short, it will become useless. Biometric authentication is also difficult to breach. The devices should be allowed by the user as trusted devices for the application. The sensitive or high-value transactions can be verified before proceeding using MFA. 

**- What MFA methods are you using in your daily life?**

- Authentication apps like Microsoft Authenticator
- SMS codes
- Email verification
- Fingerprint scanners and face recognition before logging into an app
- Push notifications
- Security question before logging in to the banking app on a new device

**- What attacks exist against different forms of 2FA?**

Through phony websites, emails, or text messages that seem to be from a reliable source, attackers deceive victims into disclosing their second-factor information. The attacker can access the account when the user enters their second factor. This exploit attacks 2FA via both SMS and email. 
Attackers may send phishing emails or messages asking users to directly supply their second-factor code under the pretense that it is required for security. In this scam, users voluntarily divulge their codes.
Attackers may pose as the user and call the service provider in an effort to reset the user's 2FA settings or obtain the user's second-factor information under false pretenses.
An attacker may access the second factor if a device used for 2FA (such as a smartphone with an authentication app) goes missing or is stolen without the necessary security precautions (such as a device lock).
This assault goes after SMS-based 2FA. Attackers who have previously obtained the username and password of a user attempt to get in using those credentials before hastily entering the required 2FA code before it ends.

## Task 3

Card fraud has changed substantially over time, influenced by developments in technology, payment systems, and the state of the world economy. The many types of card fraud, geographical variances, shifts in the fraud landscape from 2008 to 2019, the effects of technologies and legislation, transaction trends, and the importance of the internet and e-commerce in card fraud are all explored in this summary. It also covers the value of stopping data breaches and the process of tokenization.

There are a few types of card fraud including a variety of illegal behaviors, such as when physical payment cards are taken, forged, or skimmed at ATMs or point-of-sale terminals, this is known as card-present fraud, fraud using cards that are not physically present (card-not-present fraud, or CNP fraud) is a prevalent occurrence in online and over-the-phone transactions, utilizing of Lost or Stolen Cards: Criminals utilize stolen or lost cards to make illicit purchases, carrying out fraudulent transactions, fraudsters enter a user's account without authorization, frequently through phishing or data breaches and fraud with a card that is not physically present by frequently involving online purchases where the cardholder is not physically present.

Depending on the locale, different card fraud types may be more or less common. Card-present fraud is frequently more prevalent in developed nations with established financial systems, while card-not-present fraud may be more prevalent in emerging economies due to weak card infrastructure and expanding e-commerce.

Over the past ten years, a number of variables have caused the fraud environment to change significantly. Many nations embraced EMV chip technology, which by making it difficult to counterfeit chip cards, greatly decreased card-present fraud. As card-present fraud declined, thieves turned their attention to CNP fraud as e-commerce and internet transactions became more common increasing the CNP fraud. Large-scale data breaches exposed the personal information of millions of cardholders, which increased account takeover and CNP fraud. Also, thieves made use of technology by employing cunning strategies including phishing, malware, and social engineering to acquire credit card information.

Due to its susceptibility to data breaches and the rise of online commerce, CNP fraud significantly increased over the past ten years. Criminals targeted vulnerabilities in internet security, frequently gaining card information through breaches or utilizing credentials that had been stolen for fraudulent purchases.

Updating legislation and technologies were crucial in the fight against card fraud. By making it difficult for thieves to copy cards, the widespread adoption of EMV chip + PIN technology decreased card-present theft. Tokenization of payment cards reduced the value of stolen data and improved security by replacing card data with tokens. Stringent standards for data protection under regulations like the GDPR compelled firms to strengthen their security protocols.

There were substantial changes in the transaction landscape. Payments made without a card have become increasingly popular since they are quick, easy, and secure for small-value purchases. Mobile wallets with biometric authentication, such as Apple Pay and Google Pay, have grown in popularity. As online shopping took over as the primary form of retail, CNP fraud grew more common. Due to the intangibility of digital products and services, transactions involving them have become high-risk, making it difficult to detect fraud.

Card fraud was transformed by the internet and e-commerce since they gave thieves new opportunities to make money. Due to its widespread use and the anonymity of online transactions, e-commerce has become a haven for CNP fraud. Phishing, malware, and social engineering were all used by criminals to prey on unwary customers.

Fighting card fraud requires preventing data breaches. Sensitive cardholder data is exposed in breaches, which can result in fraud and account takeovers. Data protection requires effective cybersecurity protections, encryption, access controls, and frequent security assessments.

Tokenization of payment cards has proven crucial in lowering card fraud. Tokens are used in place of the card data, making the stolen data meaningless. Tokenization is frequently used to provide security for customers and businesses in digital wallets, online shopping, and mobile payments.

Card-present fraud has changed to card-not-present fraud, demonstrating how adaptable criminals are to security measures. The popularity of mobile wallets and contactless payments shows how crucial ease and security are in determining transaction choices. Card fraud is still largely driven by data breaches, which emphasizes the importance of having effective data protection measures in place and adhering to laws like the GDPR. The significance of protecting online transactions is highlighted by the continuing expansion of e-commerce, making technology like credit card tokenization more and more important.

As a result of changes in transaction preferences, legal changes, and technological developments, card fraud has developed. In order to overcome these difficulties and guarantee the security of payment card transactions, data breaches must be avoided and security measures like payment card tokenization must be put in place.


## Task 4

### Pretask

Summarize in a few sentences what is a subdomain takeover?

A subdomain takeover occurs when attacker gains control over a subdomain of a target domain. This typically happens when the subdomain's DNS (Domain Name System) record points to an external service or resource that the attacker can manipulate. If no host is available for the subdomain, an attacker can take over that subdomain by providing their own virtual host and then hosting their own content for it.


