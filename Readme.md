# The Interlocking Aiger Benchmark

## Introduction

This benchmark are for model checker researchers who are interested in **practical interlocking** problems.

All the aiger models here are generated from practical interlocking systems. Subject to confidential agreements, we cannot tell the name of our industrial partners or show sensitive data here. If you are an interlocking company, and are willing to share your data, please contact us.

## File Organization

```
|─ License
|─ Readme.md
|─ Small
	└── Alice 							// Station 
|─ Medium
	└── Bob
|─ Big
	|── Charlie
	|── David
	└── Eve
    	|──  safe						// safe ones
    	└──  unsafe						// unsafe ones
			|── Eve-00032.aig			
			|── ...
```

## Station Size

| station | Track | Route | Switch | Signal |
| ------- | ----- | ----- | ------ | ------ |
| Alice   | 14    | 8     | 3      | 12     |
| Bob     | 56    | 70    | 14     | 37     |
| Charlie | 171   | 503   | 87     | 152    |
| David   | 151   | 720   | 79     | 145    |
| Eve     | 151   | 499   | 74     | 140    |

## Attention

Aiger file that is empty means the property always holds. To keep pace with practical circumstances, we reserve them.
