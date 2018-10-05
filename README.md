# mavenversionsdemo

This project contains a three level dependency:

- root
  - parent
    - project 1
    - project 2
    
all projects are built in dependency order.

## Commands

**for version change:** mvn versions:set -DnewVersion=_&lt;target version&gt;_

examples:

**snapshot upgrade:** mvn versions:set -DnewVersion=1.1-SNAPSHOT

**release switch:** mvn versions:set -DnewVersion=1.0