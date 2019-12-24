# Overview

Architect is the Urban Planner orchestrator. Unlike the API component it is not a jailed process (Although it is conceivable to have jails within jails and as such the whole system could be held in a jail hostning numerous other  sub-jails.)

Communications between the API and the Orchestrator are done via an mTLS authenticated REST interface.

The Orchestrator can create, maintain and delete jails based on .blueprint specifications. Those specifications are stored on the filesystem for now but it is envisageable to have them stored in a DB backed storage.

# Installation

It is installed by default when [installing the API](https://github.com/sjolicoeur/urban_planner_api/).
