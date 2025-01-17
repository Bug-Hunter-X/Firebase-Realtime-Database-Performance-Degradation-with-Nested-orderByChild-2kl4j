# Firebase Realtime Database Performance Issue with Nested orderByChild Queries

This repository demonstrates a performance issue encountered when using nested `orderByChild` queries in Firebase Realtime Database with large datasets.  The issue manifests as significant slowdown or application crashes due to inefficient client-side filtering.

The `nestedOrderByChildBug.js` file shows the problematic code. The `nestedOrderByChildSolution.js` file demonstrates a more efficient approach using pagination and client-side filtering optimizations.  Consider using Firebase's server-side filtering capabilities where possible for improved performance.  For very large datasets, consider alternative database solutions better suited for complex querying.