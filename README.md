# UTF-B00F
UTF-B00F is an algorithm for encoding binary data as valid UTF16 text.
This allows arbitrary binary data to be transported via any UTF text protocol (e.g. XML) with approx 12.5% overhead.
It was inspired by the ASCII85 algorithm, which has approx 25% overhead.

Please view utf-b00f_specification.html for a detailed explanation of how the algorithm works. A reference encoder and decoder are also provided.
