# React useEffect Hook Missing Return Statement

This repository demonstrates a common error in React: forgetting the return statement in a `useEffect` hook.  This can lead to memory leaks and unexpected behavior.

## The Problem

The provided `bug.js` file contains a `useEffect` hook that's missing a return statement. This return statement is crucial for cleaning up after the component unmounts, preventing memory leaks and potential race conditions if the effect has asynchronous operations.