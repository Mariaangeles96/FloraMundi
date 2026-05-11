# FloraMundi
Práctica de examen usando FloraMundi como ejemplo

## Jerarquía
-Dirección
  --Confidencial
  --Libre
-Calidad
-Operativa
  --Producción
  --Logística
-Comercial_Marketing
-Legal

## Etiquetas 
-Sede: espana, paises_bajos, colombia, kenia
-Producto: lirios, rosas, claveles, orquídeas
-Tipo documento: ficha-tecnica, certificado, contrato, guia
-Temporada: verano, navidad, invierno
-Estado: borrador, en_revisión, en_proceso, archivado, enviado, publicado, rechazado, cobrado, por_cobrar

Para la construcción de la jerarquía nos hemos basado en las áreas de negocio y según los permisos asignados al documento.

## Plantilla metadatos
---
código: FM_ES_ROS_2026_001
titulo: Ficha tecnica Rosa del Desierto
sede:espana
version: 1.1
responsables: Juan González
fecha_creacion: 01/05/2026
fecha_revision: 02/05/2026
estado: Aprobado
palabra_clave: [rosa, flor, SemillasDeOro, sus tipocC]
---

## Nomenclatura
TIPO DE DOCUMENTO: GUIAS TECNICAS DE FLORES
FM_ESROS_2026_001.PDF
FM_CLLIR_2025_034.PDF
FM:FLORAMUNDI + ES:ESPAÑA + ROS:ROSA + AÑO + Nº VERSIÓN


PEDIDOS: PED pedido+ FM FLORAMUNDI + SEDE + FECHA + Nº CLIENTE + Nº PEDIDO
PEDFM_ES_01052026_009878_0534.PDF

## Flujo de trabajo
-Issue para pedir documento o modificación --> tecnico
-Crea una rama para el documento segun tipo --> nuevas-rosas
-Edita el documento por parte del semillero
-Abre un pull Request (peticion de aprobacion)
-El verificador/responsable Aprueba y hace Merge
-Le coloca la etiqueta de Publicado y lo coloca en la carpeta Documentos_publicos o la Web....


Estado inicial del documentos
que actor tiene que hacer 
que tiene que hacer (tarea, condiciones, plazo)
y cual seria el estado siguiente

Contrato

---Borrador Tecnico RRHH --Redactarlo-- EnRevision
EnRevision-- Responsable RRHH- Revisar y validar--Aprobado
Aprobado-- CEO-- Firmar y sellar-- Publico


##Estados del documento= Ciclo de vida del documento
Borrador
EnRevision
Aprobado
Publico
Archivado
Eliminado

## Usuarios previstos

                   Director  ResponsableArea   Editor         Externo
Pedido             Ver            Ver/editar    Crear           Nada
Guia tecnica       Ver               Ver        Crear/Editar     Ver
Contrato laboral   Editar             Ver        No              No



