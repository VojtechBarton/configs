# nf-core/configs: RCX Bioinformatics facility

nf-core pipelines have been successfully configured for use on the RCX Bioinformatics facility.

To use the RCX_BIO profile, run the pipeline with `-profile rcx_bio`. This will download and apply ['rcx_bio.config'](../conf/rcx_bio.config) which has been configured for the RCX Bioinformatics facility. This profile will allow all Nextflow processes to run within singularity containers.

> Note: This profile does not configure resources.

The RCX Bioinformatics facility has Nextflow pre-installed on the metacentrum cluster, and can be accessed by running `module load nextflow` or `module load nextflow/<version>` prior to running your pipeline. Additional singularity variables may need to be configured, such as a scratch directory, temp directory, cache directory, etc. If assistance is needed, please contact RCX Bioinformatics group.
