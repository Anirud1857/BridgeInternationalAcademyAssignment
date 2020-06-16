# BridgeInternationalAcademyAssignment
1) This solution is written using Visual Studio 2017.
2) I have tried to separate out the implementation in terms of 3 layers: Repo, Business and Implementation.
3) The implementation I initially started was building a web api and exposing various operations. But then due to time constraint I am having right with office work, I went with the standard C# library.
4) This solution contains 3 projects: Actual implementation, Unit Test project and a console application to call the dll.
5) Though it does generated the each device average 24 hours data. But still there are lot of improvements which can done in terms of code structuring and implementation.
6) Few points:
   => The path of Json file is hard-coded (Please verify. Should be in config file and be changed as per using).
   => The path of the output text file is also hard-coded (Please verify. Should be in config file and be changed as per using).
7) Dependency injection must have been implemented.
8) Was also fall short of implementing the unit test using mocking the file i/o operations.
