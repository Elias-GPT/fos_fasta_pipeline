# FOS FASTA Pipeline

Pipeline reproducible para descargar secuencias FASTA del gen humano FOS, calcular estadísticas básicas y generar gráficas sencillas.

## Objetivo

Este repositorio sirve como práctica introductoria de cómputo científico y bioinformática:

1. Descargar secuencias FASTA desde terminal.
2. Organizar un proyecto reproducible.
3. Analizar secuencias con Python.
4. Generar tablas, resúmenes y figuras simples.
5. Versionar el proyecto con Git y subirlo a GitHub.

## Gen seleccionado

Para esta tarea se eligió el gen humano **FOS**, que codifica la proteína **c-Fos**, un factor de transcripción relacionado con el complejo AP-1.

Los parámetros usados fueron:

GENE_SYMBOL="FOS"
ORGANISM="Homo sapiens"
UNIPROT_ACCESSION="P01100"
NCBI_NUCCORE_ID="NM_005252"
PROTEIN_PREFIX="FOS_protein"
MRNA_PREFIX="FOS_mRNA"

## Ejecución del pipeline

Desde la raíz del repositorio se ejecutó:

bash scripts/run_pipeline.sh

## Archivos generados principales

Los dos archivos solicitados para la tarea son:

results/FOS_protein_summary.txt
results/FOS_mRNA_summary.txt

También se generaron archivos CSV en data/processed/ y figuras PNG en figures/.

## Entrega

Para esta tarea se entrega:

1. results/FOS_protein_summary.txt
2. results/FOS_mRNA_summary.txt
3. Enlace al repositorio de GitHub
