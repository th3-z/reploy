# Reploy  
Super simple web deployment script.

## Requirements  
    * python3
    * rsync

## Todo  
    * Desktop integration
    * Pipe rsync -v into an output beautifier

Warning! This tool will delete any files in `REMOTE\_HOST:DEPLOY\_PATH` that 
don't exist in the working directory. Backup before first run.

Dotfiles are ecluded by default, see `.rexclude`.

