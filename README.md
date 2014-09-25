Ableton Live Batch Extract Project And Collect All And Save
===========================================================

This is a workflow for OSX Automator.

Given a directory, it performs the following steps for each *.als entry:
  - opens the set with an app named `Ableton Live 9 Suite`
  - saves the set under the same name but one level up
  - runs `Collect All And Save` (blindly accepting whatever your options you'd previously selected)

### use
  - (re-)launch Ableton Live 9 Suite
  - open the workflow, click Run
  - choose the project directory containing multiple *.als entries
  - pray to the FSM

On the real: this is guaranteed to not work correctly for you. It's a quick solution to my problem of moving several hundred live sets into their own, self-contained projects. Don't run this without reading the code.
