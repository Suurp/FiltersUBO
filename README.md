# 🛡️ uBlock-CustomFilters

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![uBlock Origin](https://img.shields.io/badge/uBlock%20Origin-Compatible-red.svg)](https://github.com/gorhill/uBlock)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Suurp/uBlock-CustomFilters/graphs/commit-activity)

**🚀 Advanced filter lists for bypassing and optimizing shortlinks and faucets**

[🇺🇸 English](#-english) • [🇪🇸 Español](#-español)

</div>

---

## 🇺🇸 English

> **⚠️ IMPORTANT NOTICE**
> 
> This project is for **educational and research purposes**. These filters use advanced techniques including script manipulation, timer optimization, automation, and client-side bypasses. While these are common in browser extensions and user scripts, please be aware of website Terms of Service. [Learn more](#️-disclaimer).

### 📋 Description

uBlock-CustomFilters is a collection of advanced filter lists designed specifically for **uBlock Origin**, focused on bypassing restrictions and optimizing your experience on:

#### 🔗 LinkGuard Filter (Shortlinks Bypass)
Advanced filters to bypass shortlink restrictions and optimize navigation:
- ⚡ **Bypass shortlinks** automatically - skip intermediate pages
- 🚫 **Remove ads** and intrusive advertisements
- 🔓 **Bypass anti-adblock** detection and warnings
- ❌ **Block redirections** and unwanted jumps
- 🚀 **Speed up timers** - reduce waiting times
- 🪟 **Remove popups** and pop-unders

#### 💰 CryptoBlock Filter (Faucets Optimizer)
Specialized filters to optimize crypto faucets and PTC sites:
- 🎯 **Bypass PTC restrictions** - view ads faster
- 🚫 **Remove intrusive ads** and banners
- 🔓 **Bypass anti-adblock** on faucet sites
- 🖼️ **Remove iframes** and unnecessary frames
- ⚡ **Boost timers** - reduce claim waiting times
- 🚀 **Optimize navigation** on earning sites
- 💎 **Improve faucet claiming** experience

### 🚀 Installation

You can subscribe to individual lists based on your needs, or use both for complete optimization.

#### 📋 Available Lists

| List | Purpose | Subscribe |
|------|---------|-----------|
| 🔗 **LinkGuard** | Bypass shortlinks, remove ads, speed up timers | [📥 Subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-shortlinks.txt&title=LinkGuard%20-%20Shortlinks%20Bypass) |
| 💰 **CryptoBlock** | Optimize faucets, bypass PTCs, boost timers | [📥 Subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-faucets.txt&title=CryptoBlock%20-%20Faucets%20Optimizer) |

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
   
   **LinkGuard (Shortlinks Bypass):**
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-shortlinks.txt
   ```
   
   **CryptoBlock (Faucets Optimizer):**
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-faucets.txt
   ```
6. 💾 Click **"Apply changes"**
7. ⚙️ **IMPORTANT:** Configure trusted lists (see section below)

### ⚙️ Required: Configure Trusted Lists

**This step is mandatory for the filters to work correctly.**

These filters use advanced techniques like scriptlet injection and timer manipulation that require trust configuration.

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

**Note:** This configuration tells uBlock Origin to trust filters from this repository, allowing advanced features like timer manipulation, scriptlet injection, and bypass techniques to work properly.

### 🔄 Updates

The lists are regularly updated with new bypass techniques and improvements. uBlock Origin will automatically update the filters according to its settings (by default, every few days).

**🔧 To update manually:**
1. Open the uBlock Origin dashboard
2. Go to **"Filter lists"**
3. Click the clock icon **🕐** (Update now)

### ⚠️ Warnings and Limitations

- These lists are provided **"as-is"** for personal use
- Some sites may update their anti-bypass mechanisms
- Timer manipulation may not work on all sites
- **Ethical use only** - respect website terms of service
- **⚡ Important**: Recommended to use **only with uBlock Origin's default filters**
  - Default filters include: EasyList, EasyPrivacy, Peter Lowe's Ad and tracking server list, and malware lists
  - Adding other third-party lists may cause **conflicts** or **errors**
  - If you experience issues, verify that you only have default filters + uBlock-CustomFilters active

### 🎯 Features Breakdown

#### LinkGuard (Shortlinks) includes:
- ✨ Auto-bypass for popular shortlink services
- 🚀 Timer speed boost (reduce wait times)
- 🛡️ Anti-adblock bypass
- 🚫 Ad and popup removal
- 🔄 Automatic redirection handling
- 📊 Works with: link-to.net, exe.io, ouo.io, and many more

#### CryptoBlock (Faucets) includes:
- 💰 PTC (Paid-To-Click) optimization
- ⏱️ Claim timer boost
- 🖼️ Iframe removal
- 🚫 Anti-adblock bypass for faucets
- 🎯 Captcha optimization
- 💎 Works with: faucetpay sites, autofaucets, PTC sites

### 🤝 Contributing

Contributions are welcome! You can help in the following ways:

#### 🐛 Report issues
- **Sites not bypassing**: Shortlinks or faucets that still require manual steps
- **Broken functionality**: Sites that don't work properly with filters
- **New sites**: Request support for new shortlink or faucet sites
- Specify which list the issue relates to (LinkGuard or CryptoBlock)

#### 💡 How to contribute
1. **[📝 Open an Issue](https://github.com/Suurp/uBlock-CustomFilters/issues/new)** with specific details
2. **[🔀 Create a Pull Request](https://github.com/Suurp/uBlock-CustomFilters/pulls)** with your improvements
3. 📎 Provide URL examples and describe the bypass technique needed

### 📊 Statistics

- 📦 **Lists available**: 2 (LinkGuard + CryptoBlock)
- 🕐 **Last update**: See recent commits
- 🏷️ **Categories covered**: Shortlinks bypass, faucets optimization, timer boost, anti-adblock bypass
- ⚡ **Performance**: Optimized filters with bypass capabilities
- 🔄 **Updates**: Regular updates with new bypass techniques

### 🛠️ Advanced Usage

#### Testing Bypass Functionality

After installing the filters:

1. 🧪 Visit a shortlink site (e.g., link-to.net, exe.io)
2. ⚡ Check if timers are reduced or bypassed
3. 📊 Open uBlock Origin logger to see active filters
4. ✅ Verify automatic bypassing works

#### Troubleshooting

**If bypass isn't working:**
- ✅ Verify you configured `trustedListPrefixes` correctly
- ✅ Clear browser cache and cookies
- ✅ Check logger for blocked scripts
- ✅ Disable other extensions temporarily
- ✅ Report the site if issue persists

#### Best Practices

- 🔐 Use these filters **ethically** and respect website ToS
- ⚡ Don't abuse bypass features
- 💪 Support websites you use regularly
- 📊 Report broken bypasses to help improve filters

### 🔗 Related Resources

- 📚 [uBlock Origin Wiki](https://github.com/gorhill/uBlock/wiki)
- 🛡️ [uBlock Origin Resources Library](https://github.com/gorhill/uBlock/wiki/Resources-Library)
- 📖 [Scriptlet Documentation](https://github.com/gorhill/uBlock/wiki/Resources-Library)
- 💬 [uBlock Origin subreddit](https://www.reddit.com/r/uBlockOrigin/)

### ❓ FAQ

<details>
<summary><b>Are these filters legal?</b></summary>

Yes. These filters automate what a user could do manually. However, always respect website terms of service and use ethically.
</details>

<details>
<summary><b>Will these filters speed up timers?</b></summary>

Yes. Many timers can be accelerated or bypassed entirely. However, effectiveness varies by site and their anti-bypass measures.
</details>

<details>
<summary><b>Do I need both lists?</b></summary>

No. Choose based on your usage:
- Use **LinkGuard** if you frequently use shortlink services
- Use **CryptoBlock** if you use crypto faucets or PTC sites
- Use **both** if you use both types of sites
</details>

<details>
<summary><b>Why do I need to configure trustedListPrefixes?</b></summary>

These filters use advanced techniques (scriptlet injection, timer manipulation) that require explicit trust. This is a security feature of uBlock Origin.
</details>

<details>
<summary><b>A site stopped working after installing these filters</b></summary>

Please [open an issue](https://github.com/Suurp/uBlock-CustomFilters/issues/new) with:
1. The URL of the site
2. Which list is causing the problem
3. Browser console errors (F12 → Console tab)
4. Logger output from uBlock Origin

We'll investigate and fix compatibility issues.
</details>

<details>
<summary><b>Can I contribute my own bypass filters?</b></summary>

Absolutely! We welcome contributions. Please:
1. Test your filters thoroughly
2. Document the bypass technique used
3. Ensure filters are ethical and non-malicious
4. Submit a Pull Request with clear description
</details>

<details>
<summary><b>Do these filters work on mobile?</b></summary>

Yes, if you're using Firefox for Android with uBlock Origin. Chrome mobile doesn't support extensions.
</details>

### 📜 License

📄 This project is licensed under the MIT License. See the [`LICENSE`](./LICENSE) file for details.

**TL;DR:** You can use, modify, and distribute these filters freely. Use responsibly and ethically. No warranty is provided.

### ⚖️ Disclaimer

These filters are for **educational and personal use only**. Users are responsible for complying with website terms of service. The authors are not responsible for any misuse of these filters.

---

## 🇪🇸 Español

> **⚠️ AVISO IMPORTANTE**
> 
> Este proyecto es para **propósitos educativos e investigación**. Estos filtros usan técnicas avanzadas incluyendo manipulación de scripts, optimización de timers, automatización y bypasses del lado del cliente. Aunque estas técnicas son comunes en extensiones de navegador y user scripts, ten en cuenta los Términos de Servicio de los sitios. [Más información](#️-descargo-de-responsabilidad).

### 📋 Descripción

uBlock-CustomFilters es una colección de listas de filtros avanzadas diseñadas específicamente para **uBlock Origin**, enfocadas en bypassear restricciones y optimizar tu experiencia en:

#### 🔗 Filtro LinkGuard (Bypass de Shortlinks)
Filtros avanzados para bypassear restricciones de shortlinks y optimizar la navegación:
- ⚡ **Bypass automático de shortlinks** - salta páginas intermedias
- 🚫 **Elimina anuncios** y publicidad intrusiva
- 🔓 **Bypasea anti-adblock** detección y advertencias
- ❌ **Bloquea redirecciones** y saltos no deseados
- 🚀 **Acelera timers** - reduce tiempos de espera
- 🪟 **Elimina popups** y pop-unders

#### 💰 Filtro CryptoBlock (Optimizador de Faucets)
Filtros especializados para optimizar faucets de crypto y sitios PTC:
- 🎯 **Bypass de restricciones PTC** - visualiza anuncios más rápido
- 🚫 **Elimina anuncios intrusivos** y banners
- 🔓 **Bypasea anti-adblock** en sitios de faucets
- 🖼️ **Elimina iframes** y marcos innecesarios
- ⚡ **Boost de timers** - reduce tiempos de espera para claims
- 🚀 **Optimiza navegación** en sitios de ganancias
- 💎 **Mejora experiencia** de reclamación en faucets

### 🚀 Instalación

Puedes suscribirte a listas individuales según tus necesidades, o usar ambas para optimización completa.

#### 📋 Listas Disponibles

| Lista | Propósito | Suscribirse |
|-------|-----------|-------------|
| 🔗 **LinkGuard** | Bypass shortlinks, eliminar ads, acelerar timers | [📥 Suscribirse](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-shortlinks.txt&title=LinkGuard%20-%20Shortlinks%20Bypass) |
| 💰 **CryptoBlock** | Optimizar faucets, bypass PTCs, boost timers | [📥 Suscribirse](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-faucets.txt&title=CryptoBlock%20-%20Faucets%20Optimizer) |

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
   
   **LinkGuard (Bypass de Shortlinks):**
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-shortlinks.txt
   ```
   
   **CryptoBlock (Optimizador de Faucets):**
   ```
   https://raw.githubusercontent.com/Suurp/uBlock-CustomFilters/refs/heads/main/filters-faucets.txt
   ```
6. 💾 Haz clic en **"Aplicar cambios"**
7. ⚙️ **IMPORTANTE:** Configura las listas de confianza (ver sección abajo)

### ⚙️ Requerido: Configurar Listas de Confianza

**Este paso es obligatorio para que los filtros funcionen correctamente.**

Estos filtros usan técnicas avanzadas como inyección de scriptlets y manipulación de timers que requieren configuración de confianza.

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

**Nota:** Esta configuración le indica a uBlock Origin que confíe en los filtros de este repositorio, permitiendo que funciones avanzadas como manipulación de timers, inyección de scriptlets y técnicas de bypass funcionen correctamente.

### 🔄 Actualizaciones

Las listas se actualizan regularmente con nuevas técnicas de bypass y mejoras. uBlock Origin actualizará automáticamente los filtros según su configuración (por defecto, cada varios días).

**🔧 Para actualizar manualmente:**
1. Abre el panel de uBlock Origin
2. Ve a **"Listas de filtros"**
3. Haz clic en el icono de reloj **🕐** (Actualizar ahora)

### ⚠️ Advertencias y Limitaciones

- Estas listas se proporcionan **"tal cual"** para uso personal
- Algunos sitios pueden actualizar sus mecanismos anti-bypass
- La manipulación de timers puede no funcionar en todos los sitios
- **Uso ético solamente** - respeta los términos de servicio de los sitios web
- **⚡ Importante**: Se recomienda usar **únicamente con los filtros predeterminados** de uBlock Origin
  - Los filtros predeterminados incluyen: EasyList, EasyPrivacy, Peter Lowe's Ad and tracking server list, y las listas de malware
  - Agregar otras listas de terceros puede causar **conflictos** o **errores**
  - Si experimentas problemas, verifica que solo tengas activos los filtros por defecto + uBlock-CustomFilters

### 🎯 Desglose de Características

#### LinkGuard (Shortlinks) incluye:
- ✨ Auto-bypass para servicios populares de shortlinks
- 🚀 Boost de velocidad de timers (reduce tiempos de espera)
- 🛡️ Bypass de anti-adblock
- 🚫 Eliminación de anuncios y popups
- 🔄 Manejo automático de redirecciones
- 📊 Funciona con: link-to.net, exe.io, ouo.io, y muchos más

#### CryptoBlock (Faucets) incluye:
- 💰 Optimización de PTC (Paid-To-Click)
- ⏱️ Boost de timers de claim
- 🖼️ Eliminación de iframes
- 🚫 Bypass de anti-adblock para faucets
- 🎯 Optimización de captchas
- 💎 Funciona con: sitios faucetpay, autofaucets, sitios PTC

### 🤝 Contribuir

¡Las contribuciones son bienvenidas! Puedes ayudar de las siguientes maneras:

#### 🐛 Reportar problemas
- **Sitios que no se bypassean**: Shortlinks o faucets que aún requieren pasos manuales
- **Funcionalidad rota**: Sitios que no funcionan correctamente con los filtros
- **Nuevos sitios**: Solicitar soporte para nuevos sitios de shortlinks o faucets
- Especifica a qué lista se refiere el problema (LinkGuard o CryptoBlock)

#### 💡 Cómo contribuir
1. **[📝 Abrir un Issue](https://github.com/Suurp/uBlock-CustomFilters/issues/new)** con detalles específicos
2. **[🔀 Crear un Pull Request](https://github.com/Suurp/uBlock-CustomFilters/pulls)** con tus mejoras
3. 📎 Proporciona ejemplos de URLs y describe la técnica de bypass necesaria

### 📊 Estadísticas

- 📦 **Listas disponibles**: 2 (LinkGuard + CryptoBlock)
- 🕐 **Última actualización**: Ver commits recientes
- 🏷️ **Categorías cubiertas**: Bypass de shortlinks, optimización de faucets, boost de timers, bypass de anti-adblock
- ⚡ **Rendimiento**: Filtros optimizados con capacidades de bypass
- 🔄 **Actualizaciones**: Actualizaciones regulares con nuevas técnicas de bypass

### 🛠️ Uso Avanzado

#### Probar Funcionalidad de Bypass

Después de instalar los filtros:

1. 🧪 Visita un sitio de shortlinks (ej: link-to.net, exe.io)
2. ⚡ Verifica si los timers se reducen o bypassean
3. 📊 Abre el logger de uBlock Origin para ver filtros activos
4. ✅ Verifica que el bypass automático funcione

#### Solución de Problemas

**Si el bypass no funciona:**
- ✅ Verifica que configuraste `trustedListPrefixes` correctamente
- ✅ Limpia caché y cookies del navegador
- ✅ Revisa el logger para scripts bloqueados
- ✅ Desactiva otras extensiones temporalmente
- ✅ Reporta el sitio si el problema persiste

#### Mejores Prácticas

- 🔐 Usa estos filtros **éticamente** y respeta los ToS de los sitios
- ⚡ No abuses de las funciones de bypass
- 💪 Apoya los sitios que usas regularmente
- 📊 Reporta bypasses rotos para ayudar a mejorar los filtros

### 🔗 Recursos Relacionados

- 📚 [Wiki de uBlock Origin](https://github.com/gorhill/uBlock/wiki)
- 🛡️ [Biblioteca de Recursos de uBlock Origin](https://github.com/gorhill/uBlock/wiki/Resources-Library)
- 📖 [Documentación de Scriptlets](https://github.com/gorhill/uBlock/wiki/Resources-Library)
- 💬 [Subreddit de uBlock Origin](https://www.reddit.com/r/uBlockOrigin/)

### ❓ Preguntas Frecuentes

<details>
<summary><b>¿Son legales estos filtros?</b></summary>

Sí. Estos filtros automatizan lo que un usuario podría hacer manualmente. Sin embargo, siempre respeta los términos de servicio del sitio web y úsalos éticamente.
</details>

<details>
<summary><b>¿Estos filtros acelerarán los timers?</b></summary>

Sí. Muchos timers pueden ser acelerados o bypaseados completamente. Sin embargo, la efectividad varía según el sitio y sus medidas anti-bypass.
</details>

<details>
<summary><b>¿Necesito ambas listas?</b></summary>

No. Elige según tu uso:
- Usa **LinkGuard** si frecuentemente usas servicios de shortlinks
- Usa **CryptoBlock** si usas faucets de crypto o sitios PTC
- Usa **ambas** si usas ambos tipos de sitios
</details>

<details>
<summary><b>¿Por qué necesito configurar trustedListPrefixes?</b></summary>

Estos filtros usan técnicas avanzadas (inyección de scriptlets, manipulación de timers) que requieren confianza explícita. Esta es una característica de seguridad de uBlock Origin.
</details>

<details>
<summary><b>Un sitio dejó de funcionar después de instalar estos filtros</b></summary>

Por favor [abre un issue](https://github.com/Suurp/uBlock-CustomFilters/issues/new) con:
1. La URL del sitio
2. Qué lista está causando el problema
3. Errores de consola del navegador (F12 → pestaña Console)
4. Salida del logger de uBlock Origin

Investigaremos y corregiremos problemas de compatibilidad.
</details>

<details>
<summary><b>¿Puedo contribuir mis propios filtros de bypass?</b></summary>

¡Absolutamente! Damos la bienvenida a contribuciones. Por favor:
1. Prueba tus filtros exhaustivamente
2. Documenta la técnica de bypass utilizada
3. Asegúrate de que los filtros sean éticos y no maliciosos
4. Envía un Pull Request con descripción clara
</details>

<details>
<summary><b>¿Estos filtros funcionan en móvil?</b></summary>

Sí, si estás usando Firefox para Android con uBlock Origin. Chrome móvil no soporta extensiones.
</details>

### 📜 Licencia

📄 Este proyecto está bajo la Licencia MIT. Ver el archivo [`LICENSE`](./LICENSE) para más detalles.

**En resumen:** Puedes usar, modificar y distribuir estos filtros libremente. Úsalos responsable y éticamente. No se proporciona garantía.

### ⚖️ Descargo de Responsabilidad

Estos filtros son para **uso educativo y personal únicamente**. Los usuarios son responsables de cumplir con los términos de servicio de los sitios web. Los autores no son responsables de ningún mal uso de estos filtros.

---

<div align="center">

**[⬆ Back to top](#-ublock-customfilters) • [🐛 Report an issue](https://github.com/Suurp/uBlock-CustomFilters/issues)**

Made with ❤️ for optimized browsing

</div>
