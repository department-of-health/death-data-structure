# Death data structure

Exploratory data structure. Initially based on examination of the exemplar forms
in the [Death Certification Reforms consultation](https://www.gov.uk/government/consultations/death-certification-reforms).

## The death

The event. The wrapper for the other pieces.

* [The case](json/case.json)

## Participants

Who might be part of the establishment of a cause of death? Both in terms of a
defined role and being an information source?

* [The deceased](json/deceased.json)
* [Next of kin](json/next-of-kin.json)
* [The deceased’s GP](json/practice-gp.json)
* [The deceased’s hospital consultant](json/hospital-consultant.json)
* [The deceased’s last carer](json/last-carer.json)
* The qualified attending practitioner (QAP)
* [The medical examiner](json/medical-examiner.json)
* Medical examiner’s officer
* The coroner
* Coroner’s officer
* [The registrar of births, deaths and marriages](json/registrar.json)

## Roles

Who is authoring the Medical Certificate of Cause of Death?
Who verified the fact of death?

## Cause of death

What is the cause of death? Increments of how the agreed cause was arrived at.
(Structure currently directly lifted from forms, needs interrogation)

* [Cause of death](json/cause.json)
* [Cause of death (neonatal)](json/cause-neonatal.json)

## Establishment of cause timeline

(May be part of cause of death data?) Who communicated to who, what did they
decide, when did they decide it, etc?
