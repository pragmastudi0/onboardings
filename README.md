# 🚀 Cuestionario Onboarding - Pragma Studio

Cuestionario interactivo de descubrimiento para proyectos de desarrollo.

## 📋 Características

- ✅ 56 preguntas organizadas en 4 bloques
- ✅ Navegación visual tipo Moodle (comprimible/expandible)
- ✅ Múltiples respuestas por pregunta
- ✅ Respuestas libres en texto
- ✅ Copiar respuestas al portapapeles
- ✅ Descargar respuestas como HTML
- ✅ 100% responsive (mobile-first)
- ✅ Sin dependencias externas

## 🚀 Despliegue en Vercel

### Opción 1: CLI (Recomendado)

```bash
# 1. Instala Vercel CLI
npm install -g vercel

# 2. Navega a la carpeta del proyecto
cd ruta/del/proyecto

# 3. Despliega
vercel

# Sigue las instrucciones interactivas
# Tu app estará disponible en: https://[nombre].vercel.app
```

### Opción 2: GitHub + Vercel Web

1. **Sube el proyecto a GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Conecta Vercel a GitHub**
   - Ve a https://vercel.com
   - Haz click en "New Project"
   - Selecciona tu repositorio
   - Click en "Deploy"

### Opción 3: Arrastra y suelta (Más rápido)

1. Comprime esta carpeta en un ZIP
2. Ve a https://vercel.com/import
3. Arrastra y suelta el ZIP
4. Listo! 🎉

## 📁 Estructura del proyecto

```
.
├── index.html              # Formulario principal
├── onboarding-quiz.html    # Copia del formulario
├── vercel.json             # Config de Vercel
├── package.json            # Metadata del proyecto
├── README.md              # Este archivo
└── INSTRUCCIONES.txt      # Guía de usuario
```

## 🎯 Cómo usar

1. **Accede a tu URL de Vercel**
   - Ejemplo: `https://onboarding-quiz.vercel.app`

2. **Responde el cuestionario**
   - Navega usando los números del sidebar
   - Selecciona múltiples opciones si corresponde
   - Escribe respuestas libres en texto

3. **Comparte las respuestas**
   - Botón "📋 Copiar respuestas" → pega en WhatsApp/email
   - Botón "⬇️ Descargar HTML" → guarda en tu computadora

## 🔧 Personalización

### Cambiar el nombre del proyecto en Vercel

Edita `vercel.json` y agrega:
```json
{
  "name": "mi-proyecto-custom"
}
```

### Agregar dominio personalizado

1. En Vercel Dashboard, ve a tu proyecto
2. Settings → Domains
3. Agrega tu dominio personalizado

## 📱 Compatibilidad

- ✅ Chrome, Firefox, Safari
- ✅ iOS y Android
- ✅ Tablets y desktops
- ✅ Navegador de WhatsApp

## 🔒 Datos

- ✅ Todas las respuestas se guardan LOCALMENTE en el navegador
- ✅ NO se envían datos a servidores
- ✅ Totalmente privado y seguro

## 💡 Tips

**Para compartir por WhatsApp:**
```
Envía este link:
👉 https://[tu-dominio].vercel.app

O copia las respuestas:
1. Completa el cuestionario
2. Click en "📋 Copiar respuestas"
3. Pega en WhatsApp
```

**En caso de problemas:**
- Limpia el caché del navegador (Ctrl+Shift+Del)
- Intenta en otro navegador
- Verifica la conexión a internet (para cargar las fonts)

## 📞 Soporte

- WhatsApp: +54 9 3513 91-1596
- Email: pragmasolucionesdigitales@gmail.com

---

**Hecho con ❤️ por Pragma Studio**
Desarrollo de software a medida · Córdoba, Argentina
