# Things to explore
Throughout the GSoC period, there have and will continue to be things that pique my interest and will be worth exploring in the future.
This serves as a list of things that I find during the GSoC period.

| Date (approx) | Item | Other Notes |
|---------------|------|-------------|
| May | ML clustering algorithms | Disconnect in ability to detect what tolerances can be. What do ML methods assign? |
| June 5 | Putting together standardized list of tolerances | Users don't know what to assign when using QARTOD |
| June 30 | Get all of the unit tests parametrized | Possibly something important for future contributors to look at homogenizing the whole toolbox |
| July 7 | CRC test | Extremely niche and may be out of scope/encroach on manufacturer tests |
| July 28 | Check typing | Could Literal/Union from `typing` be used in our functions? |
| July 28 | Add location bound fuzziness | When doing this test, users should be able to specify how accurate their location data is within a few meters. Add that as a tolerance of the shape object, and flag points within said tolerance as SUSPECT |
| August 4 | Check np.array() vs np.asarray() usage | Potential to save memory during tests by using np.asarray(), assuming the original does not need to be preserved. |
| August 5 | Run through Jupyter notebooks | Confirm they still work. Fix/rework them if they don't. Get them on the docs. Add them to the github actions to regen periodically and confirm everything still works. |
| August 5 | Explore interpolation flagging schemes | Add an interpolation function to the data and attempt to get as many tangents as possible. Then, flag points that are not within the interpolated window. |
| August 10 | Consistency check | Look through the functions and homogenize the coding style with helper functions, like a `valid` masker for NaNs |
| August 11 | Initial flag | Current routine is to flag all as PASS, then flag on top of that. Other orgs flag as UNKNOWN first, then fill things in. This way, any points that are missed can be found in the final step |
| August 13 | Expand unit tests | `config_creator.py` is at 37% coverage and is dependent on the QARTOD API. If users are following these JSON as examples, it should be robustly tested. |
| August 13 | Standard and long names | As per [Callum's comment](https://github.com/ioos/ioos_qc/pull/235#discussion_r3776105198), `standard_name` comes from the CF library. Worth looking up which ones are in QARTOD (commenting them out if they aren't there) |
| August 18 | Function flowcharts | Potentially not worth doing, but GTSPP groups documentation as: Name, Description, History, Rules (potentially code), Flowchart. |