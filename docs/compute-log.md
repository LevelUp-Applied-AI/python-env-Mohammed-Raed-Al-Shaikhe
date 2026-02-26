==================================================
SYSTEM INFORMATION
==================================================
OS:         Windows 11
Version:    10.0.26200
Machine:    AMD64
Processor:  AMD64 Family 23 Model 104 Stepping 1, AuthenticAMD
Python:     3.14.0 (tags/v3.14.0:ebf955d, Oct  7 2025, 10:15:03) [MSC v.1944 64 bit (AMD64)]

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.1501 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.1685 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters
  Time:    0.0295 seconds

==================================================
SUMMARY
==================================================
  sum benchmark:    0.1501s
  list benchmark:   0.1685s
  string benchmark: 0.0295s


## RAM
Total Physical Memory: 7,502 MB