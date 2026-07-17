# Lab 08 - MVP Decision

## 1. Decision

-   [x] Continue with minor revisions

## 2. Evidence Supporting the Decision

Validation testing showed an **80% task success rate** and an **average
interest level of 4.2/5** across five testers. The core booking workflow
(search tutor → view profile → submit booking → confirmation) was easy
to understand and valuable to users. The only major issue was the
unclear booking status labels, while the remaining issues were minor UI
wording problems. Therefore, the MVP should continue with targeted
improvements instead of a major redesign.

## 3. Requirements to Keep

  Requirement ID   Reason
  ---------------- -----------------------------------------------------------
  FR-01            Homepage was understood quickly by all testers
  FR-03            Booking workflow was successfully completed by most users
  FR-06            Tutor search function worked effectively
  FR-07            Tutor profile page was considered useful
  FR-11            Confirmation message was clear and reassuring

## 4. Requirements to Improve

  -----------------------------------------------------------------------
  Requirement ID          Problem Found           Improvement Needed
  ----------------------- ----------------------- -----------------------
  FR-08                   Booking status labels   Add status legend,
                          were unclear            tooltip, and clearer
                                                  visual labels

  FR-03                   Time-slot and notes     Add placeholders and
                          fields caused confusion structured time-slot
                                                  picker

  FR-06                   Search bar lacked       Increase size and
                          visibility              visual emphasis
  -----------------------------------------------------------------------

## 5. Prototype Changes Before Next Lab

-   Add a booking status legend/tooltip.
-   Replace the free-text time-slot field with a structured picker.
-   Add placeholder text to the notes field.
-   Improve the visibility of the tutor search bar.

## 6. GitHub Issues Created

  -----------------------------------------------------------------------
  Issue Title             Assigned Member         Requirement ID
  ----------------------- ----------------------- -----------------------
  Add booking status      Min Myat Maung          FR-08
  legend/tooltip to                               
  dashboard                                       

  Replace time-slot text  Eaint Shwe Sin          FR-03
  field with structured                           
  picker                                          

  Add placeholder/example Eaint Shwe Sin          FR-03
  text to booking notes                           
  field                                           

  Increase visual         Shwe Yi Htet            FR-06
  prominence of tutor                             
  search bar                                      
  -----------------------------------------------------------------------
