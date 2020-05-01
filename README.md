<p align="center">
  <a href="#rocket-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#ballot_box_with_check-goals">Goals</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#checkered_flag-installation">Installation</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licence">Licence</a>
</p>

## :rocket: About the project

A application to storage projects using [Express](https://expressjs.com/pt-br/).

## :ballot_box_with_check: Goals

Apply all the main concepts of NodeJS and Express. How to use global/local middlewares, how to do a CRUD (Create, Read, Update, Delete) and learn the behavior of the requests and responses.

## :checkered_flag-installation: Installation
`yarn install`

To start the application:

`yarn dev` 

### Routes

- `POST /projects`: This route receives the id and title in the body of the request. Creating a project like this format: `{ title: 'NewProject', owner: 'Name' }`;

- `GET /projects`: This route list all the projects storaged

- `PUT /projects/:id`: This route update a project, receiving the `id` as a route param and the `title` in the request body.

- `DELETE /projects/:id`: This route delete a project, receiving the `id` of the specific project as a route param.

## :memo: Licence

MIT Licence. See the file [LICENSE](LICENSE.md) for more details.

---
