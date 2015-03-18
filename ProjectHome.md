Advanced information processing technologies are often applied to large profiles and result in detailed behavior analysis. Moreover, under the pretext of increased personalization and strong accountability, organizations exchange information to compile even larger profiles. However, the user is unaware about the amount and type of personal data kept in profiles, partially due to advanced interactions between multiple organizations during service consumption.

In this project, a formal approach to analyse privacy properties in complex electronic services is realized. A flexible framework for logic reasoning allows for formally modelling these services and inferring privacy properties that can be interpreted by the modeler.  Therefore, the inference strategy consists of compiling user profiles according to the user's expectations in the data practices of all involved service providers.

This project is realized in the IDP 3 (http://dtai.cs.kuleuven.be/krr/software/idp).  The inference strategy is specified in [theory](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/AnalyzePrivacyTrustTheory.idp).

## Webshop scenario ##
The [vocabulary](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/AnalyzePrivacyTrustVocab.idp) contains all the symbols that are required for modeling these services. This is applied to a [web shop scenario](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/scenario.txt).

The services provided by the web shop are modeled in the [input model](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/WebShopInputModel.idp).  The conclusions about the privacy properties are summarized in this [output file](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Outputwebshop.txt).

## Loyalty scenarios ##
Privacy is analyzed for two [loyalty scenarios](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/scenario.txt).  Different types of users are modeled for both scenarios, namely a user that is less concerned about his privacy (_U1_) and a user that is more concerned about it (_U2_).  User profiles are generated from these models and are analyzed for two cases, namely, in case there are no collaborations between organizations and in case there are collaborations.

### Models of loyalty scenarios ###
  * Model of [scenario 1: U1](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/01_U1_CardbasedLoyaltySystem.idp)
    * Privacy analysis in case [no collaborations exist](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/01_U1_userprofiles_NoCollab.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/01_U1_userprofiles_NoCollab.o) to results
    * Privacy analysis in case [advertisers share data to the loyalty app provider](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/01_U1_userprofiles_ADtoLAP.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/01_U1_userprofiles_ADtoLAP.o) to results

  * Model of [scenario 1: U2](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/01_U1_CardbasedLoyaltySystem.idp)
    * Privacy analysis in case [no collaborations exist](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/01_U2_userprofiles_NoCollab.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/01_U2_userprofiles_NoCollab.o) to results
    * Privacy analysis in case [advertisers share data to the loyalty app provider](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/01_U2_userprofiles_ADtoLAP.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/01_U2_userprofiles_ADtoLAP.o) to results

  * Model of [scenario 2: U1](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/02_U1_AppbasedLoyaltySystem.idp)
    * Privacy analysis in case [no collaborations exist](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/02_U1_userprofiles_NoCollab.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/02_U1_userprofiles_NoCollab.o) to results
    * Privacy analysis in case [advertisers share data to the loyalty app provider](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/02_U1_userprofiles_ADtoLAP.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/02_U1_userprofiles_ADtoLAP.o) to results
    * Privacy analysis in case [a minimum set of collaborations that is found](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/02_U1_userprofiles_xxCollab.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/02_U1_userprofiles_xxCollab.o) to results

  * Model of [scenario 2: U2](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/02_U2_AppbasedLoyaltySystem.idp)
    * Privacy analysis in case [no collaborations exist](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/02_U2_userprofiles_NoCollab.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/02_U2_userprofiles_NoCollab.o) to results
    * Privacy analysis in case [advertisers share data to the loyalty app provider](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/02_U2_userprofiles_ADtoLAP.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/02_U2_userprofiles_ADtoLAP.o) to results
    * Privacy analysis in case [a minimum set of collaborations that is found](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/02_U2_userprofiles_xxCollab.idp).
      * [Link](http://code.google.com/p/inspect-privacy-and-trust/source/browse/trunk/Loyalty%20Scenarios/Results/02_U2_userprofiles_xxCollab.o) to results


