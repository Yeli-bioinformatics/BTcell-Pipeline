# ImmuneSeq-Pipeline
A pipeline to analysis immune sequencing data using Miseq2X300 and detecting CDR3 sequence.

# Name
        BTcell_Pipe.pl
# Synopsis
        A program for doing reference-based BTcell analysis for all species;
# Description
        Do QC, mapping, VDJ gene extraction and report production.
# Usage
        perl BTcell_Pipe.pl [Options] --cfg config.file --rawdir rawdata_dir --outdir outputDir
# Options
    --cfg           <str>   config file path  [Requiried]
    --rawdir        <str>   path for rawdata directory  [Requiried].
    --outdir        <str>    path for output directory and all results will be put into the directory [Requiried].
    --queue         <str>   qsub queue option. 
    --sched_options <str>   qsub hiseqx option.
    --BI            <str>   BI name for the analysis.
# Version
        V1.0; 20161207; 
