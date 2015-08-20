WRITING NOTES
=============

* Try to include at least 2 or 3 distinct examples of how to employ each function/operator
  discussed.

 * Explain more than you'd normally think is necessary


## Prelude - How Read this Book? I know how to read

    Maybe use christopher alexander's bold, italics, indent structure to show
    what is important and what is not.
    ^ If this approach is used then give the option to render the book at different
      levels of detail and the ability to switch between them

    This book can be read chronologically for a cradle to grave exploration of using
    the FAKE build system

    You can also use the refernce links that pulls together all content in the book
    related to a particular module or topic
        e.g. `NUNIT` section would pull from testing and documentation
             `PAKET` section would pull from Build Prep and deploy




# Part 1- Introduction To FAKE
=========================================

## What is Fake and why should I care?

	* Statically typed build scripts, intellisense, type providers

	* Easily config and setup builds for multiple target frameworks

	* Examples of Interesting Ways FAKE is use
	* atom-fsharp to generate js plugin for the editor
	* fsharp.formatting + many projects to generate github-pages


## Anatomy of a Build Script

	1. Build Targets
	2. Dependency Chains
	3. Final Targets
	4. Tracing
	5. Basic Operators


# Part 2 - FAKElib
===================

## Filesystem Interaction
	### [File System](http://fsharp.github.io/FAKE/apidocs/fake-filesystem.html)
	### [File System Helper ](http://fsharp.github.io/FAKE/apidocs/fake-filesystemhelper.html)
	### [File Utils](http://fsharp.github.io/FAKE/apidocs/fake-fileutils.html)
	### [Change Watcher](http://fsharp.github.io/FAKE/apidocs/fake-changewatcher.html)

    ### Version Control - [Fake.Git]
    	* [Braches](http://fsharp.github.io/FAKE/apidocs/fake-git-branches.html)
    	* [Commit](http://fsharp.github.io/FAKE/apidocs/fake-git-commit.html)
    	* [CommandHelper](http://fsharp.github.io/FAKE/apidocs/fake-git-commandhelper.html)
    	* [CommitMessage](http://fsharp.github.io/FAKE/apidocs/fake-git-commitmessage.html)
    	* [FileStatus](http://fsharp.github.io/FAKE/apidocs/fake-git-filestatus.html)
    	* [Information](http://fsharp.github.io/FAKE/apidocs/fake-git-information.html)
    	* [Merge](http://fsharp.github.io/FAKE/apidocs/fake-git-merge.html)
    	* [Rebase](http://fsharp.github.io/FAKE/apidocs/fake-git-rebase.html)
    	* [Repository](http://fsharp.github.io/FAKE/apidocs/fake-git-repository.html)
    	* [Reset](http://fsharp.github.io/FAKE/apidocs/fake-git-reset.html)
    	* [SHA1](http://fsharp.github.io/FAKE/apidocs/fake-git-sha1.html)
    	* [SanityChecks](http://fsharp.github.io/FAKE/apidocs/fake-git-sanitychecks.html)
    	* [Staging](http://fsharp.github.io/FAKE/apidocs/fake-git-staging.html)
    	* [Stash](http://fsharp.github.io/FAKE/apidocs/fake-git-stash.html)
    	* [Submodule](http://fsharp.github.io/FAKE/apidocs/fake-git-submodule.html)


## Build Preparation

	### [ Paket ](http://fsharp.github.io/FAKE/apidocs/fake-paket.html)
	### Nuget
		* [Fake.Nuget.Install](http://fsharp.github.io/FAKE/apidocs/fake-nuget-install.html)
		* [Fake.Nuget.Update](http://fsharp.github.io/FAKE/apidocs/fake-nuget-update.html)
    ### [Process Helper](http://fsharp.github.io/FAKE/apidocs/fake-processhelper.html)
    ### [Restore Package Helper](http://fsharp.github.io/FAKE/apidocs/fake-restorepackagehelper.html)


## Build / Compilation
	### [AssemblyInfoFile](http://fsharp.github.io/FAKE/apidocs/fake-assemblyinfofile.html)
	### [AssemblyInfoHelper](http://fsharp.github.io/FAKE/apidocs/fake-assemblyinfohelper.html)
	### [GAC Helper](http://fsharp.github.io/FAKE/apidocs/fake-gachelper.html)
	### [ILMerge Helper](http://fsharp.github.io/FAKE/apidocs/fake-ilmergehelper.html)
	### [NGenHelper](http://fsharp.github.io/FAKE/apidocs/fake-ngenhelper.html)
    ### MSBuild
        * [ProjectSystem](http://fsharp.github.io/FAKE/apidocs/fake-msbuild-projectsystem.html)
        * [SpecsRemovement](http://fsharp.github.io/FAKE/apidocs/fake-msbuild-specsremovement.html)
        * [MSBuildHelper](http://fsharp.github.io/FAKE/apidocs/fake-msbuildhelper.html)

	### FSharp
		* [Compiling F# Sources](http://fsharp.github.io/FAKE/fsc.html)
    ### Other Languages
        * [TypeScript](http://fsharp.github.io/FAKE/apidocs/fake-typescript.html)
        * [VB6 Helper](http://fsharp.github.io/FAKE/apidocs/fake-vb6helper.html)

## Testing and Continuous Integration

	### [Unit Test Helper](http://fsharp.github.io/FAKE/apidocs/fake-unittesthelper.html)
	### [Unit Test Common](http://fsharp.github.io/FAKE/apidocs/fake-unittestcommon.html)
	### [Fixie Helper](http://fsharp.github.io/FAKE/apidocs/fake-fixiehelper.html)
	### [MSTest Helper](http://fsharp.github.io/FAKE/apidocs/fake-mstest.html)
	### [NUnit Common](http://fsharp.github.io/FAKE/apidocs/fake-nunitcommon.html)
	### [NUnit Parallel](http://fsharp.github.io/FAKE/apidocs/fake-nunitparallel.html)
	### [NUnit Sequential](http://fsharp.github.io/FAKE/apidocs/fake-nunitsequential.html)
	### [XUnit](http://fsharp.github.io/FAKE/apidocs/fake-testing-xunit.html)
	### [XUnit2](http://fsharp.github.io/FAKE/apidocs/fake-testing-xunit2.html)
    ### [VSTest](http://fsharp.github.io/FAKE/apidocs/fake-vstest.html)
	### [Process Test Runner](http://fsharp.github.io/FAKE/apidocs/fake-processtestrunner.html)
	### [SpecFlow Helper](http://fsharp.github.io/FAKE/apidocs/fake-specflowhelper.html)

## Generating Documentation

    ### [XML Helper](http://fsharp.github.io/FAKE/apidocs/fake-xmlhelper.html)
    ### [ReportGeneratorHelper](http://fsharp.github.io/FAKE/apidocs/fake-reportgeneratorhelper.html)
    ### [DocuHelper](http://fsharp.github.io/FAKE/apidocs/fake-docuhelper.html)
    ### [ReleaseNotesHelper](http://fsharp.github.io/FAKE/apidocs/fake-releasenoteshelper.html)
    ### [SemVerHelper](http://fsharp.github.io/FAKE/apidocs/fake-semverhelper.html)
    ### [NUnitXML](http://fsharp.github.io/FAKE/apidocs/fake-nunitxml.html)

## Package and Deploy

	### [FTP Helper](http://fsharp.github.io/FAKE/apidocs/fake-ftphelper.html)
	### [Nuget Helper](http://fsharp.github.io/FAKE/apidocs/fake-nugethelper.html)


	### Creating Achives


	### SourceLink


	### Fake.Deploy


	### [OctoTools](http://fsharp.github.io/FAKE/apidocs/fake-octotools.html)

	### [ Paket Again!](http://fsharp.github.io/FAKE/apidocs/fake-paket.html)


## Interop and You Don't Stop

    ### [UserInputHelper](http://fsharp.github.io/FAKE/apidocs/fake-userinputhelper.html)
    ### [ProcessHelper](http://fsharp.github.io/FAKE/apidocs/fake-processhelper.html)
    ### [REST](http://fsharp.github.io/FAKE/apidocs/fake-rest.html)


## Debugging and Troubleshooting Common Build Issues



# Part 3 - Recipes - CONTRIBUTIONS WELCOME!
============================================
    Got a cool target you whipped up in one of you "Build.fsx" files?
    Throw it in here under the appropriate content/purpose/function heading

-> Collect cool FAKE stuff from various F# OSS across github and bitbucket
