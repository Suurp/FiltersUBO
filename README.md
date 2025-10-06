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

- These lists are provided **"as-is"** for **educational and research purposes**
- 📚 **About These Filters**: 
  - These filters use advanced web manipulation techniques similar to those found in popular userscripts and browser extensions
  - **Techniques used**: Timer optimization, automated interactions, script modifications, and client-side bypasses
  - **Please note**: Some websites may have Terms of Service that restrict automated interactions
  - These are learning tools to understand how web filtering and automation work
  - **Recommended use**: Personal research, testing, and educational purposes
- Some sites may detect and block these techniques
- Effectiveness varies by website implementation
- Captcha bypass only works on client-side validated captchas (improperly implemented ones)
- **⚡ Important**: Recommended to use **only with uBlock Origin's default filters**
  - Default filters include: EasyList, EasyPrivacy, Peter Lowe's Ad and tracking server list, and malware lists
  - Adding other third-party lists may cause **conflicts** or **errors**
  - If you experience issues, verify that you only have default filters + uBlock-CustomFilters active

### ⚖️ Legal Notice

**Please read before using:**

These filters use techniques commonly found in browser extensions and userscripts, including:
- Timer optimization and manipulation
- Automated interactions (clicking, form filling)
- JavaScript modification (including event handling)
- Client-side captcha bypasses (only for improperly validated captchas)
- Anti-adblock detection handling
- DOM manipulation and page behavior modification

**Things to keep in mind:**
- 📜 **Terms of Service**: Some websites have policies against automation. Review site ToS before use
- 🎓 **Educational purpose**: These filters are meant for learning about web technologies and filtering
- 🔧 **Testing & Research**: Useful for understanding client-side vs server-side security
- ⚖️ **Your responsibility**: You're responsible for how you use these tools
- 🤝 **Fair use**: Consider supporting websites you frequently use

**Best used for:**
- Learning about web automation and filtering techniques
- Understanding how websites implement protections
- Personal testing and research
- Improving your browsing experience on sites you have permission to modify

**Not recommended for:**
- Large-scale automated abuse or farming
- Circumventing paid services in bad faith
- Violating website policies intentionally
- Commercial spam or fraud

### 🎯 Features Breakdown

#### 🔗 LinkGuard (Shortlinks) includes:
- ✨ Auto-bypass for popular shortlink services
- 🚀 Timer speed boost (reduce wait times)
- 🛡️ Anti-adblock bypass
- 🚫 Ad and popup removal
- 🔄 Automatic redirection handling
- 🤖 **Automated clicking** on skip buttons
- 🎯 **Script-based automation** for navigation
- 📊 Works with: link-to.net, exe.io, ouo.io, and many more

#### 💰 CryptoBlock (Faucets) includes:
- 💰 PTC (Paid-To-Click) optimization
- ⏱️ Claim timer boost
- 🖼️ Iframe removal
- 🚫 Anti-adblock bypass for faucets
- 🎯 Captcha optimization (bypasses improperly validated captchas)
- 🤖 **Auto-clicking** for claims and ads
- 🔄 **Automated form filling** and submission
- 🔓 **Captcha bypass** for client-side only validation
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

- 📚 **Learn and understand** what the filters do before using them
- 📜 **Check website policies** if you're unsure about automation rules
- 🎓 **Use for education** - great for learning about web technologies
- 🤝 **Be respectful** - consider supporting sites you use regularly
- 🛡️ **Use responsibly** - these are powerful tools, use them wisely
- 💡 **Share knowledge** - help others learn about web filtering

### 🔗 Related Resources

- 📚 [uBlock Origin Wiki](https://github.com/gorhill/uBlock/wiki)
- 🛡️ [uBlock Origin Resources Library](https://github.com/gorhill/uBlock/wiki/Resources-Library)
- 📖 [Scriptlet Documentation](https://github.com/gorhill/uBlock/wiki/Resources-Library)
- 💬 [uBlock Origin subreddit](https://www.reddit.com/r/uBlockOrigin/)

### ❓ FAQ

<details>
<summary><b>Are these filters legal to use?</b></summary>

These filters use techniques similar to those in many popular browser extensions and userscripts (like Tampermonkey scripts, Greasemonkey, etc.). The legality depends on how you use them:

- ✅ **Personal use and learning**: Generally fine for educational purposes
- ✅ **Understanding web technologies**: Totally okay
- ⚠️ **Website ToS**: Some sites prohibit automation - review their policies
- ❌ **Large-scale abuse**: Not recommended and likely against site policies

**Bottom line**: Use responsibly, respect website policies, and you'll generally be fine. These are tools for learning and personal use.
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

**In simple terms:** You can use, modify, and share these filters freely. They're provided as-is for educational purposes. Use responsibly.

### ⚖️ Disclaimer

**Before using these filters, understand:**

These filters are educational tools that demonstrate web filtering and automation techniques. Similar techniques are used in many popular browser extensions and userscripts available today.

**What you should know:**
- 🎓 **Educational focus**: Designed to help you learn about web technologies
- 📜 **Website policies**: Some sites have rules about automation - it's your responsibility to review them
- 🔧 **How you use it matters**: These are tools, and like any tool, they should be used responsibly
- 🛡️ **No guarantees**: We provide these as-is, without warranties
- 🤝 **Community project**: We maintain these for learning, not for abuse

**Use these filters to:**
- Learn about web filtering and automation
- Improve your personal browsing experience
- Understand web security concepts
- Research and test on sites where appropriate

Remember: Great power comes with great responsibility. Use these tools ethically and respectfully.

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

- Estas listas se proporcionan **"tal cual"** para **propósitos educativos y de investigación**
- 📚 **Sobre Estos Filtros**: 
  - Estos filtros usan técnicas avanzadas de manipulación web similares a las encontradas en userscripts y extensiones de navegador populares
  - **Técnicas usadas**: Optimización de timers, interacciones automatizadas, modificación de scripts y bypasses del lado del cliente
  - **Ten en cuenta**: Algunos sitios web pueden tener Términos de Servicio que restringen interacciones automatizadas
  - Estas son herramientas de aprendizaje para entender cómo funcionan el filtrado web y la automatización
  - **Uso recomendado**: Investigación personal, pruebas y propósitos educativos
- Algunos sitios pueden detectar y bloquear estas técnicas
- La efectividad varía según la implementación del sitio web
- El bypass de captchas solo funciona en captchas validados del lado del cliente (implementados incorrectamente)
- **⚡ Importante**: Se recomienda usar **únicamente con los filtros predeterminados** de uBlock Origin
  - Los filtros predeterminados incluyen: EasyList, EasyPrivacy, Peter Lowe's Ad and tracking server list, y las listas de malware
  - Agregar otras listas de terceros puede causar **conflictos** o **errores**
  - Si experimentas problemas, verifica que solo tengas activos los filtros por defecto + uBlock-CustomFilters

### ⚖️ Aviso Legal

**Por favor lee antes de usar:**

Estos filtros usan técnicas comúnmente encontradas en extensiones de navegador y userscripts, incluyendo:
- Optimización y manipulación de timers
- Interacciones automatizadas (clics, llenado de formularios)
- Modificación de JavaScript (incluyendo manejo de eventos)
- Bypasses de captchas del lado del cliente (solo para captchas validados incorrectamente)
- Manejo de detección anti-adblock
- Manipulación DOM y modificación de comportamiento de páginas

**Ten en cuenta:**
- 📜 **Términos de Servicio**: Algunos sitios web tienen políticas contra automatización. Revisa los ToS del sitio antes de usar
- 🎓 **Propósito educativo**: Estos filtros están destinados para aprender sobre tecnologías web y filtrado
- 🔧 **Pruebas e Investigación**: Útiles para entender seguridad del lado del cliente vs servidor
- ⚖️ **Tu responsabilidad**: Eres responsable de cómo uses estas herramientas
- 🤝 **Uso justo**: Considera apoyar los sitios web que usas frecuentemente

**Mejor uso para:**
- Aprender sobre técnicas de automatización y filtrado web
- Entender cómo los sitios web implementan protecciones
- Pruebas e investigación personal
- Mejorar tu experiencia de navegación en sitios donde tienes permiso para modificar

**No recomendado para:**
- Abuso automatizado a gran escala o farming
- Eludir servicios de pago de mala fe
- Violar políticas de sitios web intencionalmente
- Spam comercial o fraude

### 🎯 Desglose de Características

#### 🔗 LinkGuard (Shortlinks) incluye:
- ✨ Auto-bypass para servicios populares de shortlinks
- 🚀 Boost de velocidad de timers (reduce tiempos de espera)
- 🛡️ Bypass de anti-adblock
- 🚫 Eliminación de anuncios y popups
- 🔄 Manejo automático de redirecciones
- 🤖 **Clics automatizados** en botones de saltar
- 🎯 **Automatización basada en scripts** para navegación
- 📊 Funciona con: link-to.net, exe.io, ouo.io, y muchos más

#### 💰 CryptoBlock (Faucets) incluye:
- 💰 Optimización de PTC (Paid-To-Click)
- ⏱️ Boost de timers de claim
- 🖼️ Eliminación de iframes
- 🚫 Bypass de anti-adblock para faucets
- 🎯 Optimización de captchas (bypasea captchas validados incorrectamente)
- 🤖 **Auto-clics** para claims y anuncios
- 🔄 **Llenado y envío automático** de formularios
- 🔓 **Bypass de captchas** con validación solo del lado del cliente
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

- 📚 **Aprende y entiende** qué hacen los filtros antes de usarlos
- 📜 **Revisa políticas del sitio web** si no estás seguro sobre reglas de automatización
- 🎓 **Úsalos para educación** - excelentes para aprender sobre tecnologías web
- 🤝 **Sé respetuoso** - considera apoyar los sitios que usas regularmente
- 🛡️ **Usa responsablemente** - estas son herramientas poderosas, úsalas sabiamente
- 💡 **Comparte conocimiento** - ayuda a otros a aprender sobre filtrado web

### 🔗 Recursos Relacionados

- 📚 [Wiki de uBlock Origin](https://github.com/gorhill/uBlock/wiki)
- 🛡️ [Biblioteca de Recursos de uBlock Origin](https://github.com/gorhill/uBlock/wiki/Resources-Library)
- 📖 [Documentación de Scriptlets](https://github.com/gorhill/uBlock/wiki/Resources-Library)
- 💬 [Subreddit de uBlock Origin](https://www.reddit.com/r/uBlockOrigin/)

### ❓ Preguntas Frecuentes

<details>
<summary><b>¿Es legal usar estos filtros?</b></summary>

Estos filtros usan técnicas similares a las de muchas extensiones de navegador y userscripts populares (como scripts de Tampermonkey, Greasemonkey, etc.). La legalidad depende de cómo los uses:

- ✅ **Uso personal y aprendizaje**: Generalmente bien para propósitos educativos
- ✅ **Entender tecnologías web**: Totalmente bien
- ⚠️ **ToS de sitios web**: Algunos sitios prohíben automatización - revisa sus políticas
- ❌ **Abuso a gran escala**: No recomendado y probablemente contra políticas del sitio

**Conclusión**: Úsalos responsablemente, respeta las políticas de los sitios web, y generalmente estarás bien. Estas son herramientas para aprendizaje y uso personal.
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

**En términos simples:** Puedes usar, modificar y compartir estos filtros libremente. Se proporcionan tal cual para propósitos educativos. Úsalos responsablemente.

### ⚖️ Descargo de Responsabilidad

**Antes de usar estos filtros, entiende:**

Estos filtros son herramientas educativas que demuestran técnicas de filtrado web y automatización. Técnicas similares se usan en muchas extensiones de navegador y userscripts populares disponibles hoy.

**Lo que debes saber:**
- 🎓 **Enfoque educativo**: Diseñados para ayudarte a aprender sobre tecnologías web
- 📜 **Políticas de sitios web**: Algunos sitios tienen reglas sobre automatización - es tu responsabilidad revisarlas
- 🔧 **Cómo los uses importa**: Estas son herramientas, y como cualquier herramienta, deben usarse responsablemente
- 🛡️ **Sin garantías**: Proporcionamos estos tal cual, sin garantías
- 🤝 **Proyecto comunitario**: Mantenemos estos para aprendizaje, no para abuso

**Usa estos filtros para:**
- Aprender sobre filtrado web y automatización
- Mejorar tu experiencia de navegación personal
- Entender conceptos de seguridad web
- Investigar y probar en sitios donde sea apropiado

Recuerda: Un gran poder conlleva una gran responsabilidad. Usa estas herramientas ética y respetuosamente.

---

<div align="center">

**[⬆ Back to top](#-ublock-customfilters) • [🐛 Report an issue](https://github.com/Suurp/uBlock-CustomFilters/issues)**

Made with ❤️ for optimized browsing

</div>
