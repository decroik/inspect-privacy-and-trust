# Inspect Privacy and Trust

Advanced information processing technologies are often applied to large profiles and result in detailed behavior analysis. Moreover, under the pretext of increased personalization and strong accountability, organizations exchange information to compile even larger profiles. However, the user is unaware about the amount and type of personal data kept in profiles, partially due to advanced interactions between multiple organizations during service consumption.

In this project, a formal approach to analyse privacy properties in complex electronic services is realized. A flexible framework for logic reasoning allows for formally modelling these services and inferring privacy properties that can be interpreted by the modeler. Therefore, the inference strategy consists of compiling user profiles according to the user's expectations in the data practices of all involved service providers.

This project is realized in the IDP 3 (http://dtai.cs.kuleuven.be/krr/software/idp). The inference strategy is specified in [theory](https://github.com/decroik/inspect-privacy-and-trust/blob/master/AnalyzePrivacyTrustTheory.idp).

##Webshop scenario
The vocabulary contains all the symbols that are required for modeling these services. This is applied to a web shop scenario.

The services provided by the web shop are modeled in the input model. The conclusions about the privacy properties are summarized in this output file.

##Loyalty scenarios
Privacy is analyzed for two loyalty scenarios. Different types of users are modeled for both scenarios, namely a user that is less concerned about his privacy (U1) and a user that is more concerned about it (U2). User profiles are generated from these models and are analyzed for two cases, namely, in case there are no collaborations between organizations and in case there are collaborations.

###Models of loyalty scenarios
 * Model of scenario 1: U1
  * Privacy analysis in case no collaborations exist.
    * Link to results
  * Privacy analysis in case advertisers share data to the loyalty app provider.
    * Link to results
 * Model of scenario 1: U2
  * Privacy analysis in case no collaborations exist.
    * Link to results
  * Privacy analysis in case advertisers share data to the loyalty app provider.
    * Link to results
 * Model of scenario 2: U1
  * Privacy analysis in case no collaborations exist.
    * Link to results
  * Privacy analysis in case advertisers share data to the loyalty app provider.
    * Link to results
  * Privacy analysis in case a minimum set of collaborations that is found.
    * Link to results
 * Model of scenario 2: U2
  * Privacy analysis in case no collaborations exist.
    * Link to results
  * Privacy analysis in case advertisers share data to the loyalty app provider.
    * Link to results
  * Privacy analysis in case a minimum set of collaborations that is found.
    * Link to results
