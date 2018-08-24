To simplify the engineering, we make some assumptions that can be lifted with some effort:

- This library cannot parse JSON document of size 16MB or more.
- We expect the input memory pointer to 256-bit aligned and to be padded (e.g., with spaces) so that it can be read entirely in blocks of 256 bits.
