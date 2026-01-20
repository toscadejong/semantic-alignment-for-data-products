# Pattern: The Semantic Lifecycle of Grid Operation

## Summary

Operating an electricity grid requires multiple semantic layers to work together across the lifecycle of grid development, activation, and operation.

These layers span from component design and safety, through asset and function modelling, and fit in operational and organisational use.

Components, Assets, and Functions are not hierarchical layers.
They represent different semantic states of grid reality that coexist horizontally.

Nbility provides the enterprise steering context above them, while conceptual models align their meaning across the organisation.



                Nbility (Enterprise Steering)
                        │
                        │  (semantic alignment)
                        ▼
             Conceptual Models (NBNL Vocabulary)
                        │
                        │  (semantic mapping)
                        ▼
   ┌────────────┬────────────┬────────────┐
   │ Components │   Assets   │ Functions  │   ← Horizontal semantic layers
   └────────────┴────────────┴────────────┘
              CIM (Formal Structure)
                        │
                        ▼
                  Data Products


---

With inside Functions the perspectives preserved:

Function Semantics
├── Grid Perspective
├── Market Perspective
└── Enterprise Perspective

---

### 1. Operational & Organisational Semantics  
**What does it require to operate and maintain an electricity grid?**

- Maintenance  
- Planning  
- Congestion management  
- Decision-making  
- Accountability  

This layer uses the sector-aligned organisational steering model Nbility.

Nbility does not replace CIM’s enterprise perspective.  
It provides a broader framework for structuring how the organisation operates the grid.

## The Semantic Layers of Grid Operation

### 2. Component & Safety Semantics  
**What is allowed to exist**

- Components and assemblies  
- Engineering constraints  
- Safety and compliance rules  
- Supplier specifications  
- System engineering models (e.g. SysML)  

This layer defines what may safely and legally become part of the grid.

---

### 3. Asset Semantics  
**What exists in the grid**

- Commissioned physical assets  
- Equipment, terminals, connectivity  
- Installed infrastructure  

This layer represents the physical reality of the grid.

CIM provides the core structural language for this.

---

### 4. Function Semantics  
**What the grid does**

- Network functions  
- Capacity, flow, protection  
- Operational roles of assets  

This layer represents the functional behaviour of the grid, separate from the physical assets themselves.

CIM explicitly supports this distinction.

---

### 5. CIM Perspectives  
**How the same grid is viewed**

CIM preserves multiple perspectives on the same asset–function reality:

- Grid perspective – physical and operational structure  
- Market perspective – roles, exchanges, flexibility  
- Enterprise perspective – organisational and business context  

These perspectives are views, not separate layers.

They interpret the same underlying asset–function structure.


---

## Why Asset–Function Separation Matters

Assets and functions are not the same thing:

| Asset | Function |
|------|----------|
| Physical object | Behaviour / role |
| Exists in space | Exists in operation |
| Installed | Executed |
| Structural | Dynamic |

Merging them leads to:

- Overloaded concepts  
- Poor modelling clarity  
- Confused responsibilities  
- Reduced interoperability  

CIM’s separation should be preserved.

---

## Role of Data Products

Data products act as semantic carriers:

- They expose asset and function data  
- They reference business concepts (NBNL)  
- They align with enterprise capabilities (Nbility)  
- They express ownership and responsibility  

They do not replace semantic models —  
they operationalise them across teams.

---

## Key Insight

Grid operation is not just technical.

It is a layered semantic system:

- Organisations defines which capabilities, processes and data are necessary and how they fit together
- Safety defines what may exist  
- Assets define what exists  
- Functions define what happens  
- Perspectives define how it is viewed  

Each layer remains distinct, but aligned.
