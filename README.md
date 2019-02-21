# docker-vue-cli
A Docker image for Vue projects using vue-cli@3.4.1

# Execution

Create a project folder

In Windows
```
docker run -it --rm --name vue -v ${PWD}:/usr/app/vuser -p 8080:8080 edwinjbc87/vue-cli:3.4.1
```

# Vue Project Creation
Create a project using yarn package manager
```
vue create . -m yarn
```

# Author
* **Edwin Bonifacio** [edwinjbc87][https://github.com/edwinjbc87]

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
