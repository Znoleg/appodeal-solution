# Appodeal test

A task to test plugin development skills 👨‍💻

### A few comments:
1. All commits are independent and relate to each task separately. There are some commits that are not directly related to the task.
2. iOS build failed because the provided plugin (or its dependencies) uses a deprecated IAd framework, which causes [an error](https://discussions.unity.com/t/undefined-symbol-objc-class-adclient-in-xcode-16/1525866) when building in XCode. I could have researched how to resolve this situation, but I started and finished the task later than the original agreements, so I left it like that for now.
3. The fourth point of the task says about the implementation of GetBuildDate, but the implementation itself (in the decompiled sources) exists and it was only necessary to add implementations to the wrappers. I did not change the original implementation, since perhaps the task only implied adding the implementation to the wrappers.
