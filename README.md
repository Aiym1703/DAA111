# DAA111 – Divide & Conquer (AITU)


## Build & run
```bash
mvn -q -DskipTests=false test
mvn -q -DskipTests package
java -jar target/DAA111-1.0-SNAPSHOT.jar --algo mergesort --n 60000 --out results/ms.csv
java -jar target/DAA111-1.0-SNAPSHOT.jar --algo quicksort --n 60000 --out results/qs.csv
java -jar target/DAA111-1.0-SNAPSHOT.jar --algo select --n 60000 --out results/select.csv
java -jar target/DAA111-1.0-SNAPSHOT.jar --algo closest --n 65536 --out results/closest.csv
```

## Notes
- Metrics: comparisons, swaps, allocations, recursionDepth.
- Seeds and cutoffs are **different** from the earlier build, so CSVs/PNGs differ.
- Tests verify correctness + QuickSort depth bound.
# DAA111
