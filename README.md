# maricopa
Jetstream based secondary analysis pipeline


# Path naming structure
See https://github.com/tgen/phoenix#tgen-naming-convention for details on fastq naming conventions

```
/path/to/primary/analysis/results/.
├── patientID1
├── patientID2
├── patientID3

/path/to/family/analysis/results/STUDY_F0001/.
├── genome
│   └── joint_variant_calling
│       ├── glnexus
│       │   ├── DeepVariantWGS
│       │   │   └── STUDY_F0001
│       │   │       ├── STUDY_F0001.bcf
│       │   │       ├── STUDY_F0001.bcf.csi
│       │   └── gatk
│       │       └── STUDY_F0001
│       │           ├── STUDY_F0001.bcf
│       └── qc
│           └── DeepVariantWGS
│               └── STUDY_F0001
├── exome
.
.
.
```
