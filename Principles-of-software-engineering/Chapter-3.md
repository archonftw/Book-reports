                                                                    Modularity



Modules: Each of a set of standardized parts or independent units that can be used to construct a more complex structure
Architects must be aware of how their developers package things as it as imporant implications in architecture

Measuring Modularity
1. Cohesion: 
    It refers to what extent the parts of a module should be contained within the same module. Its a measure of how close the parts are to one another
    Ideally,all parts should be packaged together
    its a less precise measure still
    
2. Couping
    -Afferent: Measures number of incoming connections to a code artifact
    -Efferent: Measures number of outgoing connections to other code artifacts

3. Abstractness
    Its the ratio of abstract artifacts(classes,interfaces) to concrete artifacts(implementation)

    Instability=(Efferent coupling)/(Sum of both efferent and afferent coupling)    
    More the instability,more easily the codebase breaks

4. Distance from the main
    D=|A+I-1|       A->Abstractness I->Instability

5. Connascence
    Two components are said to be connascent if a change in one would require changes in other to maintain overall correctness
    ->Static:Refers to source code level coupling, degree to which something is coupled
    ->Dynamic:Analyzes calls at runtime