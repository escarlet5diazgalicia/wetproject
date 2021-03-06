# Tentative Workflow #

The few example cards and issues are supposed to show how this project layout can be useful. Generally, a common workflow could look like this:

  1. Sprint / sub-project setup
      - create (copy) a new project board for a clearly defined experimental challenge
      - optionally, define one or more Milestones in the issue tracker (e.g. "DNA synthesis xx/2018", "protein production")
      - the first card on the board "ToDo" should probably be "Construct planning"
      
  2. Construct planning
      - create "DNA request" issues for each required construct in the issue tracker
          - use the "DNA request" template and then apply the "DNA" label
          - assign them to the project board (right column in issue tracker)
      - move DNA cards to "In Progress" and update the issues with benchling and rotmic links as you progress with sequence design
     
  3. Order fragments, primers, synthetic genes
      - register final construct list in Rotmic (in issue, tick off "rotmic registration" checkbox and update links)
      - place the order (tick of "gene synthesis order" checkbox)
      
  4. DNA assembly
      - when done, register final and verified samples in Rotmic
      - close the DNA request
        - create "Problem" issues for tracking failed assemblies without getting stuck 
      - close the synthesis Milestone when all DNA requests are fulfilled
      
  5. Protein production
      - create "Protein request" issues, assign them to project board
      - prioritize proteins for production by moving them from "Backlog" to "To Do next"
      - move cards to "In progress" and update issue cards as you go along
      - close Protein requests when proteins samples are ready and registered
      - close any "protein Milestone" when all needed samples are ready
  
  6. Plan Measurements
      - create "Experiment request" for each planned experiment, assign issue to board
      - create "Material request" for each still missing material / reagent, assign to board
      - add other activities directly to board (without creating issues)
      - create new Milestone(s)
      - create new "standard protocol" pages for often repeated methods

  7. Perform Measurements
      - move "Experiment Request" card into "In Progress" column
      - update "Experiment Request" issues as you go along, create "Problem" issues if needed
      - close Experiment Request when done, work towards closing the Milestone
  
  8. Finalize project
      - optionally collect core data in repository sub-directories
      - review all open issues and cards
      - close last Milestones
      - close Project board
      - create new Project board for publication or next sprint, assign left-over issues to new Milestones and board
