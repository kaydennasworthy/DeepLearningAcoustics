# Logging into NCAR
username@casper.hpc.ucar.edu
password
two-step verification

# set up env
module load conda
modula load cuda

to activate virtual environment
conda activate dl

# run .pbs file
qsub filename.pbs

# check status 
qstat filename.2278263.casper-pbs
