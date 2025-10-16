# QSET Electrical - Payload Control Board - 2026

MCU - STM32F446VET6

## GitHub Workflow

Ensure you have cloned the repository and open the terminal.

Change the active directory to that of the local repository. 
>`cd payload_control_board_2026`

Use status to check branch and changes
>`git status` 

Pull to update changes locally
>`git pull`

In Altium, navigate to File -> Open -> Browse. Search for the files locally and open the .PrjPcb file 
`payload_control_board_2026.PrjPcb`. Proceed to edit the project. Note Altium will keep track of changes relative to your local repository and the remote repository.

Re-add the changed files to the project. 
>`git add .`

Commit to your branch. The quotation marks are part of the command.
>`git commit -m "Write your message here"`

Push changes to the remote repository.
>`git push`

## Schematic Revision Format

`Rev 1.0` -> First completed version\
`Rev 1.1` -> Minor changes (week-to-week)\
`Rev 2.0` -> Major change (operation of the circuit is different)
