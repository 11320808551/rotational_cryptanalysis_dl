# Rotational Cryptanalysis From a Differential-Linear Perspective

Abstract: The differential-linear attack, combining the power of the two most effective techniques for symmetric-key
cryptanalysis, was proposed by Langford and Hellman at CRYPTO 1994.
From the exact formula for evaluating the bias of a differential-linear distinguisher (JoC 2017),
to the differential-linear connectivity table (DLCT) technique for dealing with
the dependencies in the switch between the differential and linear parts (EUROCRYPT 2020),
and to the improvements in the context of cryptanalysis of ARX primitives (CRYPTO 2020),
we have seen significant development of the differential-linear attack during the last four years.
In this work, we further extend this framework by replacing
the differential part of the attack by rotational-xor differentials.
Along the way, we establish the theoretical link between
the rotational-xor differential and linear approximations,
revealing that it is nontrivial to directly apply the 
closed formula for the bias of ordinary differential-linear attack
to rotational differential-linear cryptanalysis.
We then revisit the rotational cryptanalysis from the
perspective of differential-linear cryptanalysis and
generalize Morawiecki et al.'s technique for analyzing Keccak,
which leads to a practical method for estimating the
bias of a (rotational) differential-linear distinguisher in
the special case where the output linear mask is a unit vector.
Finally, we apply the rotational differential-linear technique to
the permutations involved in friet, xoodoo, alzette, and siphash.
This gives significant improvements over existing cryptanalytic results,
or offers explanations for previous differential-linear distinguishers obtained
with extensive experiments without a theoretical foundation.
To confirm the validity of our analysis, all distinguishers with
practical complexities are verified experimentally.
