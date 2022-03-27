# crypto-prediction
Stock predictions of crypto assets

## User Guide
The main workhorse function is: `get_r_hat(A, B)`

To experiment with a new version, of this:
- Create a new function following the naming scheme: `get_r_hat_[EXTENSION](A, B)`
- Add `[extension]: get_r_hat_[EXTENSION]` to `r_hat_implementations`
- Change `ACTIVE_R_HAT` if running test with that version