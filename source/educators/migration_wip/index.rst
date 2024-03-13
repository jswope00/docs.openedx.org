:orphan:

Migration WIP
###########################

This is a collection of WIP docs currently being migrated from https://github.com/openedx/edx-documentation

.. toctree::
   :numbered:
   :maxdepth: 2
   :caption: Sections
   :glob:

   1_general_information/index
   2_getting-started/index
   3_dashboard_profile/index
   4_reaching_learners/index
   5_accessibility/index
   6_set_up_course/index
   7_developing_course/index
   8_course_components/index
   9_video/index
   10_exercises_tools/index
   11_course_assets/index
   12_course_features/index
   13_proctored_exams/index
   14_grading/index
   15_releasing_course/index
   16_manage_live_course/index
   17_manage_discussions/index
   18_student_progress/index
   19_rerun_course/index
   20_glossary/glossary


Editing Docs for Educators
*****************************
The educators working group is leading a project to migrate documents from the combined edx.org/Open edX legacy docs to the new Open edX docs.openedx.org. Editors who volunteer for a section should review and modify their section for: 

- Accuracy
- Outdated edx.org-specific content
- Opportunities for additional instruction
- Opportunities for additional or updated imagery
- Opportunities to reference other relevant areas of the documentation
- Opportunities for more modularity
- Tagging and organization according to the diataxis framework

Documentation editors will fork their own repository and create a branch for doing work. They will group several file changes (commits) together and submit logical groups of commits together as pull requests. Pull requests, if approved, will become part of the live docs.openedx.org site. 

Introduction & Setup
========================
1. Ensure that you have a Github account

.. note:: Create a GitHub Account
   :class: dropdown

    .. include:: ../../../how-tos/reusable_content/create_github_account.txt

2. Ensure that you have completed a CLA agreement: 

.. include:: ../../../how-tos/reusable_content/sign_agreement.txt

Fork the Repository
========================

1. Navigate to the `docs.openedx.org<https://github.com/openedx/docs.openedx.org>`_ repository
2. Fork the repository to your own GitHub account by clicking the "Fork" button at the top right of the repository page. This creates a personal copy that you can edit freely.

..image:: images/ed_1_fork_repo.png

3. Now, you will make all future edits in your forked repository. 


Create a New Branch in your Fork
===================================

1. Confirm that you are in your your own fork

Your own fork will include your username in the URL, like this: https://github.com/[my-github-username]/docs.openedx.org

2. Drop down on the branch selector and click *view all branches*

..image:: images/ed_2_view_all_branches.png

3. From the branches page, click *new branch*.

..image:: images/ed_3_new_branch.png

4. Give your branch a name with the following format: 

[github username]/revise-educators-[section #]-[section title]
e.g. 
jswope00/revise-educators-1-general-information

..image:: images/ed_4_name_new_branch.png

5. Now, you will make all future edits in your new branch. You can confirm you are working in your branch by viewing the branch drop-down in Github

..image:: images/ed_5_confirm_branch.png

Editing Files
===================================

1. Within your working branch, navigate to the file you'd like to edit. 

Most files are at source/educators/migration_wip and then within their section folder. 

2. When you've found the file you want to edit, click the pencil icon to edit in-browser

..image:: images/ed_6_suggest_edit.png

3. Make your changes

.. note:: About Documentation Changes
   :class: dropdown

    .. include:: ../../../references/doc_checklist.rst
    .. include:: ../../../references/doc_guidelines.rst
    .. include:: ../../../references/doc_templates.rst
    .. include:: ../../../references/quick_reference_rst.rst


Specifically, these are the changes we should be making throughout the documentation. 

- Review the content for accuracy
- Remove edx.org-specific content that does not apply to Open edX
- Consider adding additional instruction where needed
- Consider adding additional imagery where helpful
- Consider adding references to other docs
- Consider breaking up files for more modularity and reusability
- Tag the document according to the diataxis framework. 


Commit your Changes
===================================

1. After editing, select the “Commit changes” button.

..image:: images/ed_7_commit_changes.png

2. Select the option to commit directly to their new branch.

2. 
