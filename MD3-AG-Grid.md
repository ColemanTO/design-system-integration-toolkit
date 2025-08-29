![Token Mapping](https://github.com/ColemanTO/design-system-integration-toolkit/blob/main/MD3-AG_Grid_color_mapping_vertical.svg)

```MERMAID
graph LR
    subgraph MD3 ["Material Design 3 Color System"]
        subgraph Primary ["Primary Colors"]
            P1[primary]
            P2[on-primary]
            P3[primary-container]
            P4[on-primary-container]
        end
        
        subgraph Secondary ["Secondary Colors"]
            S1[secondary]
            S2[on-secondary]
            S3[secondary-container]
            S4[on-secondary-container]
        end
        
        subgraph Tertiary ["Tertiary Colors"]
            T1[tertiary]
            T2[on-tertiary]
            T3[tertiary-container]
            T4[on-tertiary-container]
        end
        
        subgraph Neutral ["Surface & Background"]
            N1[surface]
            N2[on-surface]
            N3[surface-variant]
            N4[on-surface-variant]
            N5[background]
            N6[on-background]
        end
        
        subgraph Outline ["Borders & Dividers"]
            O1[outline]
            O2[outline-variant]
        end
        
        subgraph State ["State Colors"]
            ST1[error]
            ST2[on-error]
            ST3[error-container]
            ST4[on-error-container]
        end
    end
    
    subgraph AGGrid ["AG Grid Color Variables"]
        subgraph Base ["Base Colors"]
            AG1[foreground-color]
            AG2[background-color]
            AG3[data-color]
            AG4[secondary-foreground-color]
        end
        
        subgraph Headers ["Header Colors"]
            AG5[header-foreground-color]
            AG6[header-background-color]
            AG7[header-cell-hover-background-color]
            AG8[header-cell-moving-background-color]
        end
        
        subgraph Rows ["Row Colors"]
            AG9[odd-row-background-color]
            AG10[even-row-background-color]
            AG11[row-hover-color]
            AG12[selected-row-background-color]
        end
        
        subgraph Borders ["Border Colors"]
            AG13[border-color]
            AG14[row-border-color]
            AG15[cell-horizontal-border]
        end
        
        subgraph Interactive ["Interactive States"]
            AG16[range-selection-border-color]
            AG17[range-selection-background-color]
            AG18[focused-cell-border-color]
            AG19[cell-data-changed-color]
        end
        
        subgraph Status ["Status & Validation"]
            AG20[invalid-color]
            AG21[checkbox-checked-color]
            AG22[input-focus-border-color]
        end
    end
    
    %% Direct Mappings
    P1 -.-|Direct| AG1
    N1 -.-|Direct| AG2
    N2 -.-|Direct| AG3
    O1 -.-|Direct| AG13
    
    %% Semantic Mappings
    P3 -.-|Selection| AG12
    S3 -.-|Headers| AG6
    T3 -.-|Hover| AG11
    N3 -.-|Alternating| AG9
    
    %% Interactive Mappings
    P2 -.-|Focus| AG18
    T1 -.-|Range Selection| AG17
    S1 -.-|Interactive| AG16
    
    %% Status Mappings
    ST1 -.-|Validation| AG20
    P1 -.-|Checked States| AG21
    P2 -.-|Focus Borders| AG22
    
    %% Calculated Mappings
    N4 -.-|Secondary Text| AG4
    P4 -.-|Header Text| AG5
    N6 -.-|Even Rows| AG10
    
    style MD3 fill:#e3f2fd,stroke:#1976d2,stroke-width:2px
    style AGGrid fill:#e8f5e8,stroke:#2e7d32,stroke-width:2px

    linkStyle default stroke-weight:2px;

```
