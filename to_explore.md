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
