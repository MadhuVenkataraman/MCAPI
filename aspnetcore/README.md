# IO.Swagger - ASP.NET Core 1.0 Server

To search, enroll, perform benefit selection and view all the eligibile benefits

## Run

Linux/OS X:

```
sh build.sh
```

Windows:

```
build.bat
```

## Run in Docker

```
cd src/IO.Swagger
docker build -t IO.Swagger .
docker run -p 5000:5000 IO.Swagger
```
