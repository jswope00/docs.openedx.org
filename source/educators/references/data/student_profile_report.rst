.. _Columns in the Student Profile Report:

===========================================
Columns in the Student Profile Report
===========================================

.. tags:: educator, reference

The student profile report includes a row for each enrolled learner or course
team member and the following columns.

 The descriptions of columns in the following table apply to standard installations of Open edX. Required
 or optional fields shown to learners during registration and available for
 editing in **Account Settings** might vary for your installation.


.. list-table::
   :widths: 30 70
   :header-rows: 1

   * - Column
     - Description
   * - id
     - The user account ID number that the system assigns to each registrant.
   * - username
     - The public username entered by the learner. Usernames are required and
       cannot be changed.
   * - name
     - The full name entered by the learner. A name is required. Learners can
       update this value on the **Account Settings** page.
   * - email
     - The email address entered by the learner. An email address is required.
       Learners can update this value on the **Account Settings** page.
   * - language
     - This column is included for backward compatibility only. This data is
       no longer collected during account creation. The selection that a
       learner makes for language on the **Account Settings** page is not
       included in this report.
   * - location
     - This column is included for backward compatibility only. The selection
       that a learner makes for **Country** during registration or for
       **Country or Region** on the **Account Settings** page is displayed in
       the "country" column of this report.
   * - year_of_birth
     - This value is optional and can be updated on the **Account Settings**
       page.
   * - gender
     - This value is optional and can be updated on the **Account Settings**
       page.
   * - level_of_education
     - This value is optional and can be updated on the **Account Settings**
       page. For a list of the possible values, see the description of the
       `auth_userprofile`_ table's level_of_education column in the
       *EdX Research Guide*.
   * - mailing_address
     - No longer collected during registration. Previously, this value was
       optional and was supplied only at registration.
   * - goals
     - This value is optional and is supplied only at registration.
   * - enrollment_mode
     - Indicates the enrollment track that the learner is enrolled in, such as
       "audit" or "verified".

   * - cohort
     - This column is included only if the course has cohorts enabled. For
       courses that include learner cohorts, shows the name of the cohort group
       that is assigned to the learner. If a learner is not assigned to a
       cohort, the value is ``[unassigned]``.
   * - team
     - This column is included only if the course has teams enabled. For courses
       that include teams, shows the name of the team that the learner belongs
       to. If a learner has not joined a team, the value is ``[unavailable]``.
   * - city
     - Data for this column is not currently collected.
   * - country
     - Learners are required to specify **Country** during registration, and can
       update this value on the **Account Settings** page.

.. seealso::
 :class: dropdown

 :ref:`Learner Data` (concept)

 :ref:`View and download student data` (how-to)

 :ref:`Access Anonymized Learner IDs <Access_anonymized>` (how-to)

