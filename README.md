# David-Mugongo
Mugongo
IT 1025
CHAPTER 8 LAB
references
jobs:
install-dependencies:
<<: *setup_env 
steps:
    -checkout
    - attach_workspace
    at: '.'
   version: 2
          -develop
          -next
          - /^release\/ .*/
