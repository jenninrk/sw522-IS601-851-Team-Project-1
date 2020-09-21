**Git Definitions**

•  Repository
  
        o       The repository is the central storage location for your project.  It is the original project file from which clones will be created and worked on by developers.  As sections of the project are refined and updated, the changes approved by the project owner(s) will be updated to this central repository.  Once the entire repository is fully fleshed out, the project will be finished.
    
•  Clone
    
        o       The clone is a local copy of the project contained within the repository on which the developer will work.  It is warehoused on the developer’s computer, typically in a directory with the nomenclature your-name/your-repo.  This file is sometimes referred to as a “working directory” or a “working tree".
     
•  Fork

        o	Allows the developer to contribute to a public repository without potentially damaging work done on the main repository by creating a copy of the main repository on the developer’s computer, and under the developer’s account. Once forked, the developer must clone the forked project in order to manipulate it. 

•   Branch

        o	A branch, or branches, are often made within a developer’s local copy, to allow them to test strategies or edits before committing changes to the main code in the master repository. 

•   Commit

        o	This command will record the changes made in the local branch back to the master repository.

•   Merge

        o	This command allows the developer to combine separate branches together. It is a useful command in that it also identifies conflicts between the branches in need of resolution for the proposed code to work. This functionality is also useful in that it is designed to preserve coding history whenever possible, limiting change management to conflicts. 

•   Checkout

        o	This command allows the developer to switch between branches.  By entering the command git checkout <branch name> , the developer switches to that identified branch, allowing them to work on that identified branch. When this command is run, the HEAD pointer moves to the last commit made in the branch the developer is working in

•   Push

        o	This command is used to update the master repository with the developer’s updated project version from the local copy. 

•   Pull

        o	This command allows the developer to request and retrieve code from a repository owner, in order to review and potentially make changes.  The repository owner will receive notification of said pull through Git Hub, and will decide whether or not to merge their repository with the proposed changes. If the repository owner elects not to merge the proposed changes into the master repository, they will click on the “Closed Pull Request” button with which they are presented, effectively rejecting the proposed change. 

•	Remote Add/Remove/Show

	o	This command is used when the main repository is forked (duplicated) for remote editing]\,t\\\v.  It is used to keep the remote fork on the developer’s computer synchronized with the original repository andany concurrent that may have been made by others upstream.  

	
