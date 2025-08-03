# tpm-make-credential-lib
Minimal spec compliant tpm2.0 make credential

# Why ? 
For some reason none of the well supported libraries like libtss ship with a software-defined tpm2_makecredential making the implementation of a Remote-Attestation protocol much harder. There are implementations floating around in Projects using TPM2 libraries, but not in a form that is easily reusable, which this repo aims to accomplish
