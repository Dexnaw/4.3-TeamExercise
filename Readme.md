# Team Exercise: Pushing and Pulling

This exercise will show the process of collaboration with different team members on a remote repository.

- Team up with the person next to you! You'll be sharing the same repository, so decide on either one of your repositories to use. If you don't have a repository yet from a previous exercise, one of the two team members can start by forking
`https://github.com/kvanrobbroeck/git-course-recipes`

- Person 1 (owner):
	- To be able to share the same repository, the repository's owner needs to add
access for the other team member. This is done using the server 's web interface.

- Person 2 (collaborator):
	- Accept the collaboration request sent to you (by email) by your team member.

- You can now collaborate on the same project. Clone (don't fork) your shared repository to your local hard drive
- We will now start a little race to be the first to push a change:

- Person 1
	- In `tiramisu.md`, change the line `1 pound mascarpone cheese` into `500g mascarpone cheese`
	- Commit your changes
	- Push your changes to the server (origin)

- Person 2
	- In `tiramisu.md`, change the line `3/4 cup white sugar` into `85g white sugar`
	- Commit your changes
	- Push your changes to the server (origin)

- You will notice that the winner (the first one to push the change) will have no issues, but the second person does! He/she will have to first pull the changes from the server, integrate (merge) that locally, and then push again.
