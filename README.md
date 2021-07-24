![imo_marine_casualties_portal.png](img/imo_marine_casualties_portal.png)
[International Maritime Organization](https://gisis.imo.org/Public/MCI/Search.aspx)

Last download was 2015.

# Abstract

This data comes from the International Maritime Organization (IMO) from the Marine Casualties and Injury.  It spans the years January 1, 1996, the date IMO numbers were required on ships to the most recent date available.  The data was downloaded on July 23 and 24.


[Sample Data](data/raw/IMO-20210723-08105484.csv)

# [Background](#background)

# International Maritime Organization

"IMO" is the abbreviation for the International Maritime Organization.  It is a specialised agency of the United Nations responsible for regulating shipping. Its headquarters is in London.  The [website](http://www.imo.org/EN/Pages/Default.aspx) had extensive information include a web [page](https://gisis.imo.org/Public/Default.aspx) with multiple data sets.  

"IMO Number" is the seven digit number following the "IMO" abbreviation and is to be displayed prominently upon the stern of ships.  IHS Maritime (formerly known as "Lloyd's Register-Fairplay") assigns the number and it stays with the ship regardless of a transfer in ownership, the country where the ship is flagged or the renaming of the vessel.  IMO numbers are assigned during construction of the ship when the keel is layed. The number was required for all ships beginning January 1, 1996.

The original International Convention for the Safety of Life at Sea (SOLAS), was adopted in 1974 and applied primarily to large merchant ships.  Over time the registration system was expaned to smaller and more diverse ships.  Originally, it applied to cargo vessels that were at least 300 gross tons (gt) and passenger vessels of at least 100 gt.

According to the Food and Agricultural Organization of the United Nations, amendments to SOLAS in 2017 now require IMO numbers for "ships of 100 gross tonnage and above, including fishing vessels of steel and non-steel hull construction […] and to all motorized inboard fishing vessels of less than 100 gross tonnage down to a size limit of 12 metres in length overall (LOA) authorized to operate outside waters under the national jurisdiction of the flag State”. (See [Unique Vessel Identifier](http://www.fao.org/global-record/background/unique-vessel-identifier/en/))

The IMO number is a six-digit sequential unique number followed by a check digit. Check digits are used to verify the accuracy of the other six digits. According to wikipedia, "this is done by multiplying each of the first six digits by a factor of 2 to 7 corresponding to their position from right to left. The rightmost digit of this sum is the check digit. For example, for IMO 9074729: (9×7) + (0×6) + (7×5) + (4×4) + (7×3) + (2×2) = 139."

From the IMO:

## Marine Casualties and Incidents

The casualty module contains two kinds of information collected on ship casualties. The first category of information is made of factual data collected from various sources and the second category of data is made of more elaborated information based on the reports of investigations into casualties received at IMO which may be full investigations reports to be analysed by the Organization or reporting forms annexed to MSC-MEPC.3/Circ.3.

## Classifications

For the purpose of collecting information on ship casualties to populate the GISIS casualty module, the Organization, selecting ship casualties according to the following classification: "very serious casualties", "serious casualties", "less serious casualties" and "marine incidents."

- "Very serious casualties" are casualties to ships which involve total loss of the ship, loss of life, or severe pollution, the definition of which, as agreed by the Marine Environment Protection Committee at its thirty-seventh session, is as follows:

 - "Severe pollution" is a case of pollution which, as evaluated by the coastal State(s) affected or the flag State, as appropriate, produces a major deleterious effect upon the environment, or which would have produced such an effect without preventive action.

- "Serious casualties" are casualties to ships which do not qualify as "very serious casualties" and which involve a fire, explosion, collision, grounding, contact, heavy weather damage, ice damage, hull cracking, or suspected hull defect, etc., resulting in:
immobilization of main engines, extensive accommodation damage, severe structural damage, such as penetration of the hull under water, etc., rendering the ship unfit to proceed*, or pollution (regardless of quantity); and/or a breakdown necessitating towage or shore assistance.

- "Less serious casualties" are casualties to ship which do not qualify as very serious casualties or serious casualties and for the purpose of recording useful information also include marine incidents which themselves include "hazardous incidents" and "near misses."

* The ship is in a condition, which does not correspond substantially with the applicable conventions, presenting a danger to the ship and the persons on board or an unreasonable threat of harm to the marine environment.

## `Ships involved` field

Ships are designated by its name.  International Maritime Numbers or the "IMO" numbers were included within the ships' name field.  The names were strings of two forms: "ship name (-)" or "ship name (IMO 1234567)". Some ships were not assigned or required to have an IMO number.  The lack of an IMO number appeared to occur with greater frequency in the earlier years. 

## Disclaimer

The GISIS casualty module contains information related to marine casualties and incidents as well as full marine safety investigation reports submitted to the International Maritime Organization by reporting Administrations. The module also contains analyses of these reports, which are aimed at identifying overall trends or issues of potential concern to the marine transportation (or to the shipping industry). No corroborating data is available and the analysis should not be used for any other purpose.The accuracy of the data available in this module cannot be guaranteed. Where appropriate, reference is made to relevant IMO instruments.
