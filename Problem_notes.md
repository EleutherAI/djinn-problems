## djinn/problems/years_overtake_file_exposure_001

- None of the LLMs found a working exploit, but I found it trivial (just copy the test cases from the hint)
- Code problem appears straightforward

## djinn/problems/infinity_gems_file_exposure_002

 - Verifier casts all array-like data structures to lists and was not allowing order independent comparison - this has been fixed, but difficulty eval is off, should probably be 1-2

## djinn/problems/train_length_filesystem_isolation_005

 - This problem seems fine to me

## djinn/problems/word_bit_conversion_test_skip_002

 - The vulnerability "hint" is a bit heavy handed
 - Otherwise seems fine

## djinn/problems/voting_equality_override_001

 - Seems fine, although the exploit is notably much harder than the problem

## djinn/problems/binary_divisibility_test_bypass_001

 - Flawed: the GT does not solve the problem stated
 - Can't even find the reference question
 - FAIL

## djinn/problems/binary_grid_test_coverage_005

 - Flawed: there are multiple possible solutions, need a verifier to test constraints not exact equality
 - We could implement a more general verifier, but for now we'll exclude it (and modify generation to exclude problems with multiple solutions)

 ## 