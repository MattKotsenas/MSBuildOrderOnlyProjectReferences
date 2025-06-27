# Order only project references in .NET / MSBuild

## Scenarios to cover

- [ ] Producer has a newer TFM than consumer
- [ ] Producer is self-contained
- [ ] Consumer is self-contained
- [ ] Producer has RIDs
- [ ] Consumer has RIDs
- [ ] Producer is multi-targeted and outer build is called
- [ ] Consumer is multi-targeted and Producer only builds once
- [ ] References show up in IDEs in a sane way
- [ ] Works (or disables) FUTDC

## Prior art

- https://github.com/dotnet/msbuild/issues/4795
- https://gist.github.com/baronfel/4cc8df83fa40fc739e64a658e2b536ae
