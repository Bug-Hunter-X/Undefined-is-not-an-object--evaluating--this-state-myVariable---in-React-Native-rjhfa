# React Native: Undefined is not an object error

This repository demonstrates a common yet tricky error in React Native: the 'undefined is not an object (evaluating 'this.state.myVariable')' error. This error typically arises when attempting to access a state variable or prop before it's been assigned a value.

## Scenario:

A component tries to use data from a state variable or prop before the component has finished mounting and the data has been loaded.  This often happens when asynchronous operations like data fetching are involved.