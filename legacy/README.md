# TURF Analysis
[TURF Analysis](https://conjoint.online/2019/11/18/turf-analysis/), an acronym for "Total Unduplicated Reach and Frequency", is a type of statistical analysis used for providing estimates of media or market potential and devising optimal communication and placement strategies given limited resources. TURF analysis identifies the number of users reached by a communication, and how often they are reached.

This library is work in progress.

### Installation

```
npm install mathjs --production --prefix ~/environment/
```

### Development progress ahead of release

Current tasks: https://github.com/Conjoint-ly/TURF-analysis/blob/master/%D0%97%D0%B0%D0%B4%D0%B0%D1%87%D0%B0.md

- [x] Search for Reach           
- [x] Allow for Frequency
- [ ] Nice outputs: Each scenario shows:
   - Reach
   - Frequency
   - For each element, unique reach ; Non-unique-reach 
- [x] Encasulate in class or prototype
- [ ] Write interface
   - Free form
   - Prepopulate with combinations of 2
   - Prepopulate with ladder
- [ ] Speed up and test robustness (repeat tests)
- [ ] Place into worker
- [ ] Validation for the interface:
   - col count in each row must be same
   - All values are numeric
 - [ ] Tests:
   - Test with 1 row only
   - Test with 1 col only 
- [ ] Clean up the repository
- [ ] Make into npm package
