moodle-format_psg
======================

[![Moodle Plugin CI](https://github.com/Behaviour-Analytics/moodle-format_psg/workflows/Moodle%20Plugin%20CI/badge.svg?branch=master)](https://github.com/Behaviour-Analytics/moodle-format_psg/actions?query=workflow%3A%22Moodle+Plugin+CI%22+branch%3Amaster)

Short description:

The Personalised Study Guide (PSG) plugin is an adaptive course format designed to
replace the Topics format.

Long description:

The PSG plugin requires the Behaviour Analytics (BA) block
(https://moodle.org/plugins/block_behaviour) to be installed and configured for
proper use. The PSG rearranges the course learning objects within the course page
based on the object's learning style (Felder and Silverman) relevance score. The
activities can be rearranged within sections and the sections can be reorganized
as well. The PSG and BA plugins work together to provide adaptive learning based
on learning style. The BA plugin has the Index of Learning Style (ILS)
questionnaire pre-made for students to take, which the PSG plugin can then use
to determine the personalisation. The PSG plugin also offers the option to use
common links, which requires a clustering analysis be made in BA, then selected
for prediction. The personalisation comes from the common links among cluster
members instead of the ILS. In addition the BA needing to be installed and
configured, the PSG plugin's scheduled task needs to run in order to populate the
database tables for correct functioning. The BA block provides a button to switch
the personalisation on and off, logging when the student switches and displaying
the data in the BA dashboard.
