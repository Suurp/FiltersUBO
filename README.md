# 🛡️ uBlock-CustomFilters
[](#-ublock-customfilters)
<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![uBlock Origin](https://img.shields.io/badge/uBlock%20Origin-Compatible-red.svg)](https://github.com/gorhill/uBlock)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Suurp/uBlock-CustomFilters/graphs/commit-activity)

**🚫 Custom filter lists for uBlock Origin**

[🇺🇸 English](#-english) • [🇪🇸 Español](#-español)

</div>

---

## 🇺🇸 English

> **⚠️ IMPORTANT NOTICE**
> 
> This project is for **educational and research purposes**. These filters use advanced techniques including script manipulation, timer optimization, automation, and client-side bypasses. While these are common in browser extensions and user scripts, please be aware of website Terms of Service. [Learn more](#️-disclaimer).

### 📋 Description

uBlock-CustomFilters is a collection of custom filter lists designed specifically for **uBlock Origin**, focused on improving your browsing experience by blocking:

#### 🔗 LinkGuard Filter (Shortlinks)
Blocks shortlink services and malicious redirect platforms used for:
- Link monetization and forced redirects
- Unwanted content jumps
- Intrusive ad injection through redirects
- Automatic unwanted redirections

#### 💰 CryptoBlock Filter (Faucets)
Blocks cryptocurrency faucets and related services that:
- Force ad views for minimal crypto rewards
- Deploy aggressive monetization tactics
- Redirect through multiple ad networks
- Execute intrusive scripts

### 🚀 Installation

You can subscribe to individual lists based on your needs, or use both for complete protection.

#### 📋 Available Lists

| List | Purpose | Subscribe |
|------|---------|-----------|
| 🔗 **LinkGuard** | Blocks URL shorteners and redirect services | [📥 Subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-shortlinks.txt&title=LinkGuard%20-%20Shortlinks%20Blocker) |
| 💰 **CryptoBlock** | Blocks cryptocurrency faucets and related sites | [📥 Subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-faucets.txt&title=CryptoBlock%20-%20Faucets%20Blocker) |

#### Method 1: Direct subscription (Recommended)

1. ✅ Make sure you have [uBlock Origin](https://github.com/gorhill/uBlock) installed
2. 🔗 Click on the **Subscribe** link for the list(s) you want from the table above
3. ✔️ Confirm the subscription in the uBlock Origin dialog
4. ⚙️ **IMPORTANT:** Configure trusted lists (see section below)

#### Method 2: Manual installation

1. 🔧 Open the uBlock Origin dashboard
2. 📋 Go to the **"Filter lists"** tab
3. ⬇️ Scroll down to **"Custom"**
4. ☑️ Check **"Import..."**
5. 📝 Paste the URL for the list you want:
   
   **LinkGuard (Shortlinks):**
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-shortlinks.txt
   ```
   
   **CryptoBlock (Faucets):**
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-faucets.txt
   ```
6. 💾 Click **"Apply changes"**
7. ⚙️ **IMPORTANT:** Configure trusted lists (see section below)

### ⚙️ Required: Configure Trusted Lists

**This step is mandatory for the filters to work correctly.**

Some filters in these lists require trust configuration. Follow these steps:

1. 🔧 Open uBlock Origin dashboard
2. ⚙️ Go to **Settings** tab
3. ☑️ Enable **"I am an advanced user"** (a gear icon ⚙️ will appear)
4. 🖱️ Click the gear icon ⚙️ that appeared next to "I am an advanced user"
5. 📝 Find the setting **`trustedListPrefixes`**
6. ✏️ Add the following to the existing value (separated by space):
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/
   ```
   
   **Example - before:**
   ```
   ublock-
   ```
   
   **Example - after:**
   ```
   ublock- https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/
   ```

7. 💾 Click **"Apply changes"**
8. 🔄 Restart your browser or reload uBlock Origin

**Note:** This configuration tells uBlock Origin to trust filters from this repository, allowing advanced filtering rules to work properly.

### 🔄 Updates

The lists are regularly updated with new domains and improvements. uBlock Origin will automatically update the filters according to its settings (by default, every few days).

**🔧 To update manually:**
1. Open the uBlock Origin dashboard
2. Go to **"Filter lists"**
3. Click the clock icon **🕐** (Update now)

### ⚠️ Warnings and Limitations

- These lists are provided **"as-is"** for personal use
- Some shorteners or faucets may bypass blocks using advanced JavaScript techniques
- There may be occasional **false positives** (legitimate sites blocked)
- **⚡ Important**: Recommended to use **only with uBlock Origin's default filters**
  - Default filters include: EasyList, EasyPrivacy, Peter Lowe's Ad and tracking server list, and malware lists
  - Adding other third-party lists may cause **conflicts** or **errors**
  - If you experience issues, verify that you only have default filters + uBlock-CustomFilters active

### 🤝 Contributing

Contributions are welcome! You can help in the following ways:

#### 🐛 Report issues
- **False positives**: Legitimate sites incorrectly blocked
- **Missing domains**: Shorteners, faucets, or redirect services that aren't blocked
- Specify which list the issue relates to (LinkGuard or CryptoBlock)

#### 💡 How to contribute
1. **[📝 Open an Issue](https://github.com/Suurp/uBlock-CustomFilters/issues/new)** with specific details
2. **[🔀 Create a Pull Request](https://github.com/Suurp/uBlock-CustomFilters/pulls)** with your suggestions
3. 📎 Provide URL examples and specify the target list

### 📊 Statistics

- 📦 **Lists available**: 2 (LinkGuard + CryptoBlock)
- 🕐 **Last update**: See recent commits
- 🏷️ **Categories covered**: Shorteners, monetization, redirects, faucets, crypto scams

### 📜 License

📄 This project is licensed under the MIT License. See the `LICENSE` file for details.

### 🙏 Acknowledgments

💙 Thanks to the uBlock Origin community and all contributors who help keep the Internet cleaner and safer.

---

## 🇪🇸 Español

> **⚠️ AVISO IMPORTANTE**
> 
> Este proyecto es para **propósitos educativos e investigación**. Estos filtros usan técnicas avanzadas incluyendo manipulación de scripts, optimización de timers, automatización y bypasses del lado del cliente. Aunque estas técnicas son comunes en extensiones de navegador y user scripts, ten en cuenta los Términos de Servicio de los sitios. [Más información](#️-descargo-de-responsabilidad).

### 📋 Descripción

uBlock-CustomFilters es una colección de listas de filtros personalizadas diseñadas específicamente para **uBlock Origin**, enfocadas en mejorar tu experiencia de navegación mediante el bloqueo de:

#### 🔗 Filtro LinkGuard (Shortlinks)
Bloquea servicios de acortadores de enlaces y plataformas de redirección maliciosas utilizadas para:
- Monetización de enlaces y redirecciones forzadas
- Saltos de contenido no deseados
- Inyección de anuncios intrusivos a través de redirecciones
- Redirecciones automáticas no deseadas

#### 💰 Filtro CryptoBlock (Faucets)
Bloquea faucets de criptomonedas y servicios relacionados que:
- Fuerzan visualización de anuncios por recompensas mínimas de crypto
- Despliegan tácticas de monetización agresivas
- Redirigen a través de múltiples redes de anuncios
- Ejecutan scripts intrusivos

### 🚀 Instalación

Puedes suscribirte a listas individuales según tus necesidades, o usar ambas para protección completa.

#### 📋 Listas Disponibles

| Lista | Propósito | Suscribirse |
|-------|-----------|-------------|
| 🔗 **LinkGuard** | Bloquea acortadores de URL y servicios de redirección | [📥 Suscribirse](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-shortlinks.txt&title=LinkGuard%20-%20Shortlinks%20Blocker) |
| 💰 **CryptoBlock** | Bloquea faucets de criptomonedas y sitios relacionados | [📥 Suscribirse](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-faucets.txt&title=CryptoBlock%20-%20Faucets%20Blocker) |

#### Método 1: Suscripción directa (Recomendado)

1. ✅ Asegúrate de tener [uBlock Origin](https://github.com/gorhill/uBlock) instalado
2. 🔗 Haz clic en el enlace **Suscribirse** de la(s) lista(s) que desees de la tabla anterior
3. ✔️ Confirma la suscripción en el cuadro de diálogo de uBlock Origin
4. ⚙️ **IMPORTANTE:** Configura las listas de confianza (ver sección abajo)

#### Método 2: Instalación manual

1. 🔧 Abre el panel de uBlock Origin
2. 📋 Ve a la pestaña **"Listas de filtros"**
3. ⬇️ Desplázate hasta **"Personalizado"**
4. ☑️ Marca **"Importar..."**
5. 📝 Pega la URL de la lista que deseas:
   
   **LinkGuard (Shortlinks):**
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-shortlinks.txt
   ```
   
   **CryptoBlock (Faucets):**
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-faucets.txt
   ```
6. 💾 Haz clic en **"Aplicar cambios"**
7. ⚙️ **IMPORTANTE:** Configura las listas de confianza (ver sección abajo)

### ⚙️ Requerido: Configurar Listas de Confianza

**Este paso es obligatorio para que los filtros funcionen correctamente.**

Algunos filtros en estas listas requieren configuración de confianza. Sigue estos pasos:

1. 🔧 Abre el panel de uBlock Origin
2. ⚙️ Ve a la pestaña **Configuración**
3. ☑️ Activa **"Soy un usuario avanzado"** (aparecerá un icono de engranaje ⚙️)
4. 🖱️ Haz clic en el icono de engranaje ⚙️ que apareció junto a "Soy un usuario avanzado"
5. 📝 Busca la configuración **`trustedListPrefixes`**
6. ✏️ Agrega lo siguiente al valor existente (separado por espacio):
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/
   ```
   
   **Ejemplo - antes:**
   ```
   ublock-
   ```
   
   **Ejemplo - después:**
   ```
   ublock- https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/
   ```

7. 💾 Haz clic en **"Aplicar cambios"**
8. 🔄 Reinicia tu navegador o recarga uBlock Origin

**Nota:** Esta configuración le indica a uBlock Origin que confíe en los filtros de este repositorio, permitiendo que las reglas de filtrado avanzadas funcionen correctamente.

### 🔄 Actualizaciones

Las listas se actualizan regularmente con nuevos dominios y mejoras. uBlock Origin actualizará automáticamente los filtros según su configuración (por defecto, cada varios días).

**🔧 Para actualizar manualmente:**
1. Abre el panel de uBlock Origin
2. Ve a **"Listas de filtros"**
3. Haz clic en el icono de reloj **🕐** (Actualizar ahora)

### ⚠️ Advertencias y Limitaciones

- Estas listas se proporcionan **"tal cual"** para uso personal
- Algunos acortadores o faucets pueden evadir los bloqueos mediante técnicas JavaScript avanzadas
- Puede haber **falsos positivos** ocasionales (sitios legítimos bloqueados)
- **⚡ Importante**: Se recomienda usar **únicamente con los filtros predeterminados** de uBlock Origin
  - Los filtros predeterminados incluyen: EasyList, EasyPrivacy, Peter Lowe's Ad and tracking server list, y las listas de malware
  - Agregar otras listas de terceros puede causar **conflictos** o **errores**
  - Si experimentas problemas, verifica que solo tengas activos los filtros por defecto + uBlock-CustomFilters

### 🤝 Contribuir

¡Las contribuciones son bienvenidas! Puedes ayudar de las siguientes maneras:

#### 🐛 Reportar problemas
- **Falsos positivos**: Sitios legítimos bloqueados incorrectamente
- **Dominios faltantes**: Acortadores, faucets o servicios de redirección que no están bloqueados
- Especifica a qué lista se refiere el problema (LinkGuard o CryptoBlock)

#### 💡 Cómo contribuir
1. **[📝 Abrir un Issue](https://github.com/Suurp/uBlock-CustomFilters/issues/new)** con detalles específicos
2. **[🔀 Crear un Pull Request](https://github.com/Suurp/uBlock-CustomFilters/pulls)** con tus sugerencias
3. 📎 Proporciona ejemplos de URLs y especifica la lista objetivo

### 📊 Estadísticas

- 📦 **Listas disponibles**: 2 (LinkGuard + CryptoBlock)
- 🕐 **Última actualización**: Ver commits recientes
- 🏷️ **Categorías cubiertas**: Acortadores, monetización, redirecciones, faucets, estafas crypto

### 📜 Licencia

📄 Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

### 🙏 Agradecimientos

💙 Gracias a la comunidad de uBlock Origin y a todos los colaboradores que ayudan a mantener Internet más limpio y seguro.

---

<div align="center">

**[⬆ Back to top](#-ublock-customfilters) • [🐛 Report an issue](https://github.com/Suurp/uBlock-CustomFilters/issues)**

Made with ❤️ for a cleaner web

</div>
