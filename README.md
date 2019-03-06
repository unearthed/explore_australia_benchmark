# Example benchmarking data for OZ Minerals Explorer challenge data science stream

This is an example of the benchmarking data so you know what to expect

For the benchmark we'll provide a number of 'stamp-sized' locations with extracted geophysical layers and the geological mapping data but without any location information. We will do this for 1000 areas around Australia with a variety of mineralizised and unmineralized areas. You can find an example in the `test_stamp` folder.

You will have to label each of these locations as to whether you think there is a deposit in the area, where that deposit is, relative to the centre of the location, and what commodities are present. For example, for the test data you'd have something like:

```csv
stamp_identifier, commodity_string, x, y, comment
test_stamp, U;Ag;Au;Cu, 0, 0, "You're looking at Promient Hill!"
```

If you think there is no deposit in the given area, just leave the commodity string empty.

We'll provide more info here on how we'll combine accuracies for presence/absence, labels and commodity types once we launch the benchmarking facility.