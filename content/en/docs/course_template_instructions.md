---
title: "New Course Template Instructions"
date: 2020-10-12T18:34:25-07:00
weight: 1001
# This document provides instructions for the central course repository template
# When the template is used to create a new course, this document is replaced by /static/admin/assets/course_template_instructions.md.template
---

### Welcome to the ModernApps Ninja New Course Template. 

#### Creating a new course

**Note:** If you do not have Collaborator or higher level permissions in the ModernAppsNinja GitHub Organization, you will need to request a new course be prepared for you by opening an issue ticket on the [https://github.com/ModernAppsNinja/modernappsninja.github.io/](https://github.com/ModernAppsNinja/modernappsninja.github.io/) repository.

To create a new course: 
- You must have Collaborator or higher level permissions in the ModernAppsNinja GitHub organization to run this workflow
- Navigate to the [create new course workflow on the actions tab of the new course template repository](https://github.com/ModernAppsNinja/course_repo_template_ct8279/actions/workflows/create_new_course.yml)

- Initiate a `create a new course workflow` action
- A New course repository will be created with the initial scaffolding setup, based on a copy of this repository
- Follow these instructions to add your content and set up the course catalog card, tests and the completion certificate
- Once you have setup the new course content, Initiate a "Publish this course" workflow from the new course template, and your new course will be published!

The github user account that initiates the course creation workflow request will be given maintainer persmissions on the new course repository, and can push or approve merges to content during course development. Once the course is ready to be published, branch protection settings will be added that will require at least two maintainers to approve changes.

Every section in this repository after the New Course Template instructions are direct copies of an early version of the ModernApps Skills 101 course. 

You may use the following sections and pages in this template as a reference. Modify, delete or add pages to customize the content in the newly created course repository with your desired course materials.

You can find additional details on how to set up tests and completion certificates on the following pages in this section.

This course template is based on Google's Docsy template, which provides detailed instructions you can use as a reference for modifying this template. Detailed instructions for the Docsy template can be found at [https://docsy.dev](https://docsy.dev).

Once you have completed preparing your desired content and have verified it is ready for live publication, please go to the actions tab of the github repository for this course and initiate the `Publish This Course` workflow. The workflow will add branch protection settings, and submit a pull request that, when approved, will display the course in the modernapps.ninja course catalog.

If you have any questions or need any assistance, please open an issue ticket on the [https://github.com/modernappsninja/modernappsninja.gitub.io](https://github.com/modernappsninja/modernappsninja.gitub.io) repository.