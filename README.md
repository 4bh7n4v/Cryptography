# Cryptography
Encryption algorithms for End to End Encryptions 
Python implementation of SHA2 and SHA3

## SHA3  
  ![image](https://github.com/user-attachments/assets/41e959cf-bbcf-427e-afac-c97b0d2054cc)

  SHA3 customisable hash based on rate of state and output lenght

  ![image](https://github.com/user-attachments/assets/015fd583-34dc-4831-a784-f716bfd9144f)

  
  The Block Transformation
  The block transformation, which is represented as the block labeled function in the above sponge function diagram is broken up in to 5 steps that are done a number   of rounds.


  Keccek-f Steps
  The 5 steps are:

  # θ (theta)  
  # ρ (rho)  
  # π (pi)  
  # χ (chi)  
  # ι (iota)
  
  In SHA-3 since we have ℓ = 6, we will do this block transformation 24 rounds for each time the function is run. The round, denoted by ir starts at 0, and is
  incremented by 1 each time the iota step finishes. Once ir =24, the output of the iota function will be the new capacity and rate This means that if we have twice
  the amount of bits to hash as the rate bits allow we must run the function 48 times, 24 times for each rate block input, r1 and r2 respectively in the sponge
  function
