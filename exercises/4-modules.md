## Modules

1. Create a shared module:
- should be in it’s own folder
- should include common components that we want to share (like the search component)
- use it in the application (remove search component from app module and import the new shared module)

2. (Extra) Create a forRoot method in the core module to prevent having multiple instances of the same provider.

3. (Extra) Create an employees module and use lazy loading to fetch it. Check in the newtwork that from dev tools that it's actually lazy loaded.

[Next exercise](5-pipes.md)

