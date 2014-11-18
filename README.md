bamdst -- a BAM Depth Stat Tool
================================
Bamdst is a lightweight tool to stat the depth coverage of 
target regions of bam file(s).
Bam file(s) should be properly sorted, and the probe file (bed
file) and the output dir must be specified in the first place.

USAGE
------
bamdst -p <probe.bed> -o . in1.bam
