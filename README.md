MoreLINQ
========

LINQ to Objects is missing a few desirable features.

This project enhances LINQ to Objects with extra methods, in a manner which 
keeps to the spirit of LINQ.

MoreLINQ is available for download and installation as
[NuGet packages](https://www.nuget.org/packages/morelinq/).

Overview of Operators
---------------------

**Operator**        | **Summary**
--------------------|------------------------------------------------------------------------------
`AssertCount`       | Asserts that a source sequence contains a given count of elements.
`Batch`             | Batches the source sequence into sized buckets.
`Concat`            | Returns a sequence consisting of the head element and the given tail elements. This operator uses deferred execution and streams its results.
`Consume`           | Completely consumes the given sequence. This method uses immediate execution, and doesn't store any data during execution.
`DistinctBy`        | Returns all distinct elements of the given source, where "distinctness" is determined via a projection and the default eqaulity comparer for the projected type.
`EquiZip`           | Returns a projection of tuples, where each tuple contains the N-th element from each of the argument sequences.
`ForEach`           | Immediately executes the given action on each element in the source sequence.
`Generate`          | Returns a sequence of values consecutively generated by a generator function.
`GenerateByIndex`   | Returns a sequence of values based on indexes.
`MaxBy`             | Returns the maximal element of the given sequence, based on the given projection.
`MinBy`             | Returns the minimal element of the given sequence, based on the given projection.
`Pad`               | Pads a sequence with default values if it is narrower (shorter in length) than a given width.
`Pipe`              | Executes the given action on each element in the source sequence and yields it.
`Prepend`           | Prepends a single value to a sequence.
`PreScan`           | Performs a pre-scan (exclusive prefix sum) on a sequence of elements.
`Scan`              | Peforms a scan (inclusive prefix sum) on a sequence of elements.
`SingleOrFallback`  | Returns the single element in the given sequence, or the result of executing a fallback delegate if the sequence is empty.
`TakeEvery`         | Returns every N-th element of a source sequence.
`ToDelimitedString` | Creates a delimited string from a sequence of values. The delimiter used depends on the current culture of the executing thread.
`Trace`             | Traces the elements of a source sequence for diagnostics.
`Zip`               | Returns a projection of tuples, where each tuple contains the N-th element from each of the argument sequences.
`ZipLongest`        | Returns a projection of tuples, where each tuple contains the N-th element from each of the argument sequences.