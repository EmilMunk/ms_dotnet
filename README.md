# ms_dotnet45 Cookbook
[![Build Status](https://travis-ci.org/tas50/ms_dotnet45.svg?branch=2.0.0)](https://travis-ci.org/tas50/ms_dotnet45)

This cookbook installs the Microsoft .NET Framework 4.5

# Requirements
- Windows cookbook

## Platform
- Windows Vista SP1 or later
- Windows Server 2008 (not supported on Server Core)
- Windows 7
- Windows Server 2008 R2 (not supported on Server Core )

# Attributes
- `default['ms_dotnet45']['http_url']`: Download URL for MS .NET 4.5 MSI
- `default['ms_dotnet45']['timeout']`: Timeout for completing the installation

# Usage
Include the default recipe on a node's runlist to ensure that .NET Framework 4.5 is installed on the system
