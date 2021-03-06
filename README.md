# Centrify.Samples.PowerShell

Notes: This package contains code samples for the Centrify Identity Service Platform API's written in PowerShell.  

The sample is broken into 3 parts:

  1. module/Centrify.Samples.PowerShell.psm1 - This is a PowerShell module which can be included with Import-Module.  The 
  module provides an MFA implementation for interactive authentication, as well as a wrapper for invoking Centrify REST api's.
  2. Centrify.Samples.PowerShell.Example.ps1 - This is an example script, which import's the Centrify.Samples.PowerShell module
  as well as a library of functions (functions/*) for common REST api endpoints.
  3. functions/*.ps1 - A set of functions broken into individual files exhibit how to invoke specific APIs using the 
  Centrify.Samples.Powershell module. 
 

Sample Functionality Includes:

    1. Utilizing interactive MFA to authenticate a user and retrieve a session for interacting with the platform
    2. Issuing queries to the report system
    3. Updating credentials on a UsernamePassword application
    4. Getting assigned apps (User Portal view)
    5. Getting assigned apps by role
    6. Creating a new CUS user
    7. Locking/Unlocking a CUS user
   