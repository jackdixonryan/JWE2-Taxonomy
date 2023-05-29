# Cladistics

```mermaid
%%{init: {"flowchart": {"htmlLabels": false}} }%%
flowchart LR;

MorosIntrepidus["Moros Intrepidus"]
trex["Tyrannosaurus Rex"]

Allosaurids["ALLOSAURIDS
* Allosaurus
 "]
 
 Metriacanthosaurids["METRIACANTHOSAURIDS
 * Metriacanthosaurus
 "]
 
 Ceratosaurids["CERATOSAURIDS
 * Ceratosaurus
 "]
 
 Megalosaurids["MEGALOSAURIDS
 * Megalosaurus
 "]
 
 Coelophysids["CEOLOPHYSIDS
 * Coelophysis
 "]


spinosaurs("`
- Baryonyx
- Suchomimus
- Spinosaurus
`")

stegosaurs("`
- Huayangosaurus 
- Gigantspinosaurus
- Chungkingosaurus
- Stegosaurus 
- Kentrosaurus
- Wuerhosaurus
`")

Chordata-->Synapsida
Chordata-->Dinosauria
Chordata-->Reptilia
Chordata-->Pterosauria

Synapsida-->Dimetrodon
Synapsida-->Lystrosaurus

Dinosauria-->Saurischia
Dinosauria-->Ornithischia

Saurischia-->Herrerrasaurus
Saurischia-->Theropoda
Saurischia-->Sauropodomorpha

Ornithischia-->Thyreophora
Ornithischia-->Ornithopoda
Ornithischia-->Ceratopsia
Ornithischia-->Pachycephalosauridae

Pachycephalosauridae-->Homalocephale
Pachycephalosauridae-->Pachycephalosaurus
Pachycephalosauridae-->Dracorex
Pachycephalosauridae-->Stygimoloch

Ceratopsia-->Ceratopsidae

Ceratopsidae-->Chasmosaurus
Ceratopsidae-->Pentaceratops
Ceratopsidae-->Nasutoceratops
Ceratopsidae-->Styracosaurus
Ceratopsidae-->Sinoceratops
Ceratopsidae-->Pachyrhinosaurus
Ceratopsidae-->Torosaurus
Ceratopsidae-->Triceratops

Thyreophora-->Stegosauria
Thyreophora-->Ankylosauria

Ornithopoda-->Dryosaurus
Ornithopoda-->Iguanodontidae
Ornithopoda-->Styracosterna
Ornithopoda-->Muttaburrasaurus
Ornithopoda-->Hadrosauridae

Hadrosauridae-->Tsintaosaurus
Hadrosauridae-->Corythosaurus
Hadrosauridae-->Parasaurolophus
Hadrosauridae-->Maiasaura
Hadrosauridae-->Edmontosaurus
Hadrosauridae-->Olorotitan

Styracosterna-->Hadrosauriformes

Hadrosauriformes-->Ouranosaurus

Iguanodontidae-->Iguanodon

Stegosauria-->stegosaurs

Ankylosauria-->Nodosauridae
Ankylosauria-->Ankylosauridae

Ankylosauridae-->Ankylosaurus
Ankylosauridae-->Minmi
Ankylosauridae-->Crichtonsaurus
Ankylosauridae-->Euoplocephalus

Nodosauridae-->Polacanthus
Nodosauridae-->Sauropelta
Nodosauridae-->Nodosaurus

Theropoda-->Megalosauridae-->Megalosaurus
Theropoda-->Coelophysidae-->Coelophysis
Theropoda-->Metriacanthosauridae-->Metriacanthosaurus
Theropoda-->Ceratosauridae-->Ceratosaurus
Theropoda-->Allosauridae-->Allosaurus
Theropoda-->MorosIntrepidus
Theropoda-->Compsognathidae
Theropoda-->Proceratosauridae
Theropoda-->Neotheropoda
Theropoda-->Tetanurae
Theropoda-->Spinosauridae
Theropoda-->Dromaeosauridae
Theropoda-->Carcharodontosauridae
Theropoda-->Ornithomimidae
Theropoda-->Megaraptora
Theropoda-->Troodontidae
Theropoda-->Oviraptoridae
Theropoda-->Deinocheiridae
Theropoda-->Abelisauridae
Theropoda-->Tyrannosauridae
Theropoda-->Therizinosauridae

Tyrannosauridae-->Albertosaurus
Tyrannosauridae-->trex
Tyrannosauridae-->Qianzhousaurus

Therizinosauridae-->Therizinosaurus

Abelisauridae-->Carnotaurus
Abelisauridae-->Majungasaurus

Deinocheiridae-->Deinocheirus

Oviraptoridae-->Oviraptor

Troodontidae-->Troodon

Megaraptora-->Megaraptoridae
Megaraptoridae-->Australovenator

Ornithomimidae-->Archaeornithomimus
Ornithomimidae-->Struthiomimus
Ornithomimidae-->Gallimimus

Carcharodontosauridae-->Acrocanthosaurus
Carcharodontosauridae-->Giganotosaurus
Carcharodontosauridae-->Carcharodontosaurus

Dromaeosauridae-->Deinonychus
Dromaeosauridae-->Velociraptor
Dromaeosauridae-->Pyroraptor
Dromaeosauridae-->Atrociraptor

Proceratosauridae-->Proceratosaurus
Proceratosauridae-->Yutyrannus

Compsognathidae-->Compsognathus
Compsognathidae-->Sinosauropteryx

Spinosauridae-->Spinosaurus
Spinosauridae-->Baryonxyx
Spinosauridae-->Suchomimus

Neotheropoda-->Dilophosaurus
Neotheropoda-->Cryolophosaurus

Sauropodomorpha-->Sauropoda

Sauropoda-->Mamenchisaurus
Sauropoda-->Diplodocidae
Sauropoda-->Macronaria
Sauropoda-->Amargasaurus
Sauropoda-->Nigersaurus

Diplodocidae-->Diplodocus
Diplodocidae-->Apatosaurus

Macronaria-->Camarasaurus
Macronaria-->Titanosauriformes
Macronaria-->Titanosauria

Titanosauria-->Lithostrotia 

Lithostrotia-->Dreadnoughtus
Lithostrotia-->Saltasauridae

Saltasauridae-->Alamosaurus

Titanosauriformes-->Brachiosaurus

Tetanurae-->Monolophosaurus

Reptilia-->Ichthyosauria
Reptilia-->Plesiosauria
Reptilia-->Squamata

Squamata-->Mosasauridae

Mosasauridae-->Tylosaurus
Mosasauridae-->Mosasaurus

Ichthyosauria-->Ichthyosauridae 
Ichthyosauridae-->Ichthyosaurus

Plesiosauria-->Plesiosauridae 
Plesiosauria-->Pliosauridae
Plesiosauria-->Elasmosauridae

Plesiosauridae-->Plesiosaurus

Elasmosauridae-->Styxosaurus
Elasmosauridae-->Elasmosaurus

Pliosauridae-->Attenborosaurus
Pliosauridae-->Liopleurodon
Pliosauridae-->Kronosaurus

Pterosauria-->Macronychoptera
Pterosauria-->Dsungaripteridae
Pterosauria-->Anurognathidae
Pterosauria-->Anhangueridae
Pterosauria-->Ornithocheirae
Pterosauria-->Tapejaridae
Pterosauria-->Pteranodontidae
Pterosauria-->Azhdarchidae
Pterosauria-->Nyctosauridae

Nyctosauridae-->Barbaridactylus

Azhdarchidae-->Quetzalcoatlus

Pteranodontidae-->Pteranodon
Pteranodontidae-->Geosternbergia

Anhangueridae-->Maaradactylus
Anhangueridae-->Cearadactylus

Tapejaridae-->Tapejara

Ornithocheirae-->Tropeognathus

Anurognathidae-->Jeholopterus

Dsungaripteridae-->Dsungaripterus

Macronychoptera-->Dimorphodontidae 
Dimorphodontidae-->Dimorphodon
```

