```mermaid
    graph TB %% Documentación del procesamiento de datos

    %% Entity[Text]

    subgraph " "
    ID1[(Datos FJD crudos)]
    ID1_desc[Documentacion/Datos/Viejos/Niko/Datos FJD/DATOS_COVID19_4_H_V9_ANONIMIZADO.xlsx]
    end

    subgraph " "
    ID2{{Crudo a dataset dinámico}}
    ID2_desc[Documentacion/Datos/Viejos/Niko/Notebooks/Descriptive Covid.ipynb]
    end


    subgraph " "
    ID3[(Datos FJD limpios: <br> híbrido, dinámico)]
    ID3_desc[Documentacion/Datos/Viejos/Niko/Datos FJD/limpios_completos.csv]
    end
    ID3.1[Intervalos recogidos por Niko]

    subgraph " "
    ID4{{Discretización}}
    ID4_desc[Funciones de Excel]
    end

    subgraph " "
    ID5[(Datos FJD limpios: <br> discreto, dinámico)]
    ID5_desc[Documentacion/Datos/Viejos/limpiosCompletos+discretizacion.xlsx]
    end
    ID5.1[Variables de Niko para árboles]

    subgraph " "
    ID6{{Selección de características}}
    ID6_desc[Documentacion/Notebooks/preprocesamiento-datos/preprocesamiento-datos.Rmd]
    end

    subgraph " "
    ID7[(Datos FJD limpios: <br> discreto, dinámico, FS)]
    ID7_desc[Documentacion/Datos/Viejos/limpiosCompleto+discreto+dinamico.xlsx]
    end

    subgraph " "
    ID8{{Conversión a estático}}
    ID8_desc[Documentacion/Notebooks/preprocesamiento-datos/preprocesamiento-datos.Rmd]
    end

    subgraph " "
    ID9[(Datos FJD limpios: <br> discreto, estático, FS)]
    ID9_desc[Documentacion/Datos/Viejos/limpiosCompleto+discreto+estatico.xlsx]
    end

    ID1 --> ID2 .-> ID3 --> ID4 .-> ID5 --> ID6 .-> ID7 --> ID8 .-> ID9

    ID3.1 --> ID4
    ID5.1 --> ID6

    %% Estilo
    classDef Datos fill:#B0C4DE,stroke:#333,stroke-width:2px;
    classDef Procesos fill:#FFA07A,stroke:#000,stroke-width:2px;
    class ID1,ID3,ID3.1,ID5,ID5.1,ID7,ID9 Datos;
    class ID2,ID4,ID6,ID8 Procesos;
    
```