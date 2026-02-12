# Logging into NCAR
username@casper.hpc.ucar.edu
password
two-step verification

# set up env
module load conda
modula load cuda

to activate virtual environment
conda activate dl

# navigate to storage location
/glade/derecho/scratch/username

# to copy files 
scp local_path destination path

# run .pbs file
qsub filename.pbs

# check status 
qstat filename.2278263.casper-pbs
