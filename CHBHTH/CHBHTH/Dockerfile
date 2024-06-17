# Use the official Microsoft ASP.NET image with .NET Framework 4.7.2
FROM mcr.microsoft.com/dotnet/framework/aspnet:4.7.2-windowsservercore-ltsc2019

# Set the working directory
WORKDIR /inetpub/wwwroot

# Copy the application files to the container
COPY . /inetpub/wwwroot

# Expose the default port for IIS
EXPOSE 80

# No specific CMD needed as the base image runs IIS by default

