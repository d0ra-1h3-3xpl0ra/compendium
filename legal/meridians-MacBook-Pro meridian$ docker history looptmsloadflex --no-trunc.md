meridians-MacBook-Pro:~ meridian$ docker history looptms/loadflex --no-trunc

IMAGE                                                                     CREATED             CREATED BY                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 SIZE                COMMENT

sha256:12aa58b5e3ee9c6353e7c272ccd14344c2b26787f65525b9a3adb72bec671e49   7 hours ago         /bin/sh -c #(nop)  ENTRYPOINT ["dotnet" "Loop.Web.dll"]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    0B                  

<missing>                                                                 7 hours ago         /bin/sh -c #(nop)  ARG DB_PASS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             0B                  

<missing>                                                                 7 hours ago         /bin/sh -c #(nop) COPY dir:70fa87509c5b2613d578c5d0e77fdf6944d35a9c452268c2e09537bc721157a5 in .                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           87.7MB              

<missing>                                                                 45 hours ago        /bin/sh -c #(nop)  EXPOSE 80                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               0B                  

<missing>                                                                 45 hours ago        /bin/sh -c #(nop) WORKDIR /app                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             0B                  

<missing>                                                                 45 hours ago        /bin/sh -c #(nop)  ENV ASPNETCORE_ENVIRONMENT=Production                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   0B                  

<missing>                                                                 45 hours ago        /bin/sh -c #(nop)  ENV db_password=                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        0B                  

<missing>                                                                 2 weeks ago         /bin/sh -c curl -SL --output aspnetcore.tar.gz https://dotnetcli.blob.core.windows.net/dotnet/aspnetcore/Runtime/$ASPNETCORE_VERSION/aspnetcore-runtime-$ASPNETCORE_VERSION-linux-x64.tar.gz     && aspnetcore_sha512='07ea922c59cd067a6195d4b8dcd1d0460033b4fc621c2cb85f1cded18e03dd46fb091398d9a21377b81a6b28705c336e85b74cfb7de986462d007703c12f539a'     && echo "$aspnetcore_sha512  aspnetcore.tar.gz" | sha512sum -c -     && mkdir -p /usr/share/dotnet     && tar -zxf aspnetcore.tar.gz -C /usr/share/dotnet     && rm aspnetcore.tar.gz     && ln -s /usr/share/dotnet/dotnet /usr/bin/dotnet   147MB               

<missing>                                                                 2 weeks ago         /bin/sh -c #(nop)  ENV ASPNETCORE_VERSION=2.1.12                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           0B                  

<missing>                                                                 2 weeks ago         /bin/sh -c apt-get update     && apt-get install -y --no-install-recommends         curl     && rm -rf /var/lib/apt/lists/*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                7.02MB              

<missing>                                                                 2 weeks ago         /bin/sh -c #(nop)  ENV ASPNETCORE_URLS=http://+:80 DOTNET_RUNNING_IN_CONTAINER=true                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        0B                  

<missing>                                                                 2 weeks ago         /bin/sh -c apt-get update     && apt-get install -y --no-install-recommends         ca-certificates                 libc6         libgcc1         libgssapi-krb5-2         libicu57         liblttng-ust0         libssl1.0.2         libstdc++6         zlib1g     && rm -rf /var/lib/apt/lists/*                                                                                                                                                                                                                                                                                                         43.8MB              

<missing>                                                                 2 weeks ago         /bin/sh -c #(nop)  CMD ["bash"]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            0B                  

<missing>                                                                 2 weeks ago         /bin/sh -c #(nop) ADD file:52a7d996761b6acc4bb35207ca6a9902086514831ac81e10874584a741871d22 in /                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           55.3MB              

meridians-MacBook-Pro:~ meridian$ 