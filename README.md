# EcemUI OTA

## Add this line to your lineage.mk

      ECEM_BUILD_TYPE := OFFICIAL

## Create a destination CMUpdater/res/values in your device tree overlay folder

And add this xml file into that folder

* [JSON](https://gist.github.com/Mbtt107/247717ca23a4abf6358fb1da8b2a9e72)

And make proper changes.

Change branch and repo name as your wish

For example:

* [SAMPLE](https://gist.github.com/Mbtt107/cb3db466fe2727b0e1cd927af5a646f3)
      
# See for name:
 After you finish compiling a build, before uploading, you need to type this into your terminal:
 
       date +%s
 
 It will generate a number, it is used in your "json" file in the local datetime.
 
 # See for MD5sum
 
 go to output folder 
 
       md5sum filename.zip
 
 # See
 
      filename = zip name
      
      version = version number
      
      romtype = build type
     
      datetime = number generate
 
      filename = Name file zip rom
 
      md5sum = MD5sum
 
      url = Direct link for download
