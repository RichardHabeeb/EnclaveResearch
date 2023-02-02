# Enclave Research
This repo gathers, categorizes, and compares knowlege on enclaves and trusted execution environments (TEEs). Note that different authors and different domains use the term "enclave" and "TEE" to mean similar things, I view this mostly as a difference of terminology for the purposes of this document.

## What are Enclaves
Since the early 2000's much research has been devoted to dealing with the problem a large, potentially untrustworthy software and hardware stack.


## Trusted Hardware Primitives for Building Enclaves

| Technology                                     | Arch          | Resources | Key Mechanism Summary | Attestation Mechanism | TCB | Kernel-Level Enclaves | Legacy Application Support | Real-Time/Availability Support | Physical Defenses | Verification | Device Support |
|------------------------------------------------|---------------|-----------|-----------------------|-----------------------|-----|-----------------------|----------------------------|--------------------------------|-------------------|--------------|----------------|
| Intel Software Guard Extensions (SGX)          | x86           |           |                       |                       |     |                       |                            |                                |                   |              |                |
| Intel TDX                                      | x86           |           |                       |                       |     |                       |                            |                                |                   |              |                |
| AMD SEV/SEV-ES/SEV-SNP                         | x86           |           |                       |                       |     |                       |                            |                                |                   |              |                |
| TrustZone + Bus Security                       | ARMv7 / ARMv8 |           |                       |                       |     |                       |                            |                                |                   |              |                |
| CCA                                            | ARMv9         |           |                       |                       |     |                       |                            |                                |                   |              |                |
| CHERI                                          | ARMv8         |           |                       |                       |     |                       |                            |                                |                   |              |                |
| RISC-V M Mode                                  | RISC-V        |           |                       |                       |     |                       |                            |                                |                   |              |                |
| Virtualization + Trusted Boot (E.g. Intel TXT) | *             |           |                       |                       |     |                       |                            |                                |                   |              |                |
| Pure Software Isolation                        | *             |           |                       |                       |     |                       |                            |                                |                   |              |                |


## Enclave Architecture
Listing of Enclave/TEE Research for Untrusted Privileged Software and Hardware
