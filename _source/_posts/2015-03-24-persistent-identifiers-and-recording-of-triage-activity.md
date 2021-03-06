---
title: 'Persistent identifiers and recording of triage activity'
changed: '2015-03-24T11:29:09'
---


<h2>Importance of persistent client and provider identifiers</h2>
<p>A number of requests for assistance have been raised regarding protocols when upgrading and/or moving Medicare Local’s databases to new systems.</p>
<p>While there are no set protocols we would like to emphasise the importance of maintaining existing ATAPS-MDS data integrity during the transfer process. In particular, you must ensure that relevant identifiers for ‘patient_key’, ‘mhpro’ and ‘referrer_code’ are maintained so that historical analysis of the dataset is not compromised. So, for example, the same person in your new system should have the same code as they had in the old system. If it is not possible to use the existing codes then a mapping between the old and new codes should be provided so that the historical data can be updated on your behalf by the ATAPS-MDS support team.</p>
<h2>Recording of ineligible patients at triage stage</h2>
<p>New patients and/or referrals that are deemed ineligible for ATAPS services at the triage stage are generally considered out of scope of the MDS and should therefore not be recorded in the ATAPS-MDS.</p>
<p>It has been brought to our attention that the conclusion “referred elsewhere” is sometimes being incorrectly used to designate referrals that either never resulted in sessions and/or which were originally deemed to be ineligible for ATAPS services. However, this code is purely intended to be used for referrals where sessions have already begun to be delivered but where the patient has been referred to another location, if they moved for example.</p>
<p>Ideally, these out of scope referrals should therefore be removed from the MDS, however this may prove onerous as there is no automatic way of deleting referrals. As an alternative, we will be adding a new conclusion: “patient ineligible”. Once we have done so, it would be greatly appreciated if existing instances of referrals incorrectly using “referred elsewhere” as their conclusion be updated to the conclusion “patient ineligible”. We will notify you when the new conclusion has been added, at this stage we anticipate early April.</p>  
