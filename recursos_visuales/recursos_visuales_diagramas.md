# DIAGRAMAS CLAVE: FINANZAS EN EL HOGAR

## 1. EL FILTRO DE PATRIMONIO (Módulo 1)

¿Es un Activo o un Pasivo?

```mermaid
graph TD
    A[¿Pone dinero en tu bolsillo?] -->|SI| B[ACTIVO ✅]
    A -->|NO| C{¿Saca dinero de tu bolsillo?}
    C -->|SI| D[PASIVO ❌]
    C -->|NO| E[COSA NEUTRA 😐]
    
    style B fill:#9f9,stroke:#333,stroke-width:2px
    style D fill:#f99,stroke:#333,stroke-width:2px
```

## 2. EL FLUJO DE CAJA REAL (Módulo 1)

Dónde se pierde el dinero.

```mermaid
sankey-beta
    Ingresos Brutos, Impuestos, 2000
    Ingresos Brutos, Ingreso Neto, 8000
    Ingreso Neto, Gastos Fijos, 4000
    Ingreso Neto, Gastos Hormiga, 1500
    Ingreso Neto, Gastos Vampiro, 1000
    Ingreso Neto, Disponible Real, 1500
```

## 3. LA REGLA 50/30/20 (Módulo 2)

El Sistema Operativo Financiero.

```mermaid
pie title Distribución Ideal del Ingreso
    "Necesidades (Sobrevivir)" : 50
    "Deseos (Disfrutar)" : 30
    "Futuro (Libertad)" : 20
```

## 4. BOLA DE NIEVE vs AVALANCHA (Módulo 3)

```mermaid
graph LR
    subgraph AVALANCHA_Matemática
    A1[Ordenar por INTERÉS % Mayor] --> A2[Pagar Máximo]
    end
    
    subgraph BOLA_NIEVE_Psicología
    B1[Ordenar por SALDO $ Menor] --> B2[Pagar Máximo]
    B2 --> B3[¡Victoria Rápida!]
    B3 --> B4[Momentum + Cashflow Liberado]
    B4 --> B5[Atacar Siguiente Deuda]
    end
    
    style BOLA_NIEVE_Psicología fill:#e1f5fe,stroke:#01579b
```

## 5. SEMÁFORO DE FONDO DE EMERGENCIA (Módulo 4)

¿Lo uso o no?

```mermaid
graph TD
    Start[¿Tengo una Emergencia?] --> Q1{¿Es Inesperado?}
    Q1 -->|NO| R1[AHORRO PROGRAMADO 🛑]
    Q1 -->|SI| Q2{¿Es Necesario/Urgente?}
    Q2 -->|NO| R2[CAPRICHO 🛑]
    Q2 -->|SI| Q3{¿Puedo pagarlo con cash corriente?}
    Q3 -->|SI| R3[USA TU SUELDO ⚠️]
    Q3 -->|NO| R4[¡ROMPER EL CRISTAL! ✅]
    
    style R4 fill:#9f9,stroke:#333,stroke-width:4px
```
