Actualizar los textos de productos en `C:\TechCardex\src\components\Products.astro` con información real verificada en el código de cada app. No se toca nada fuera de TechCardex.

**Reverzo** (marketplace de libros, React Native + Supabase)
- Tagline: "Compra y venta de libros entre lectores, con clubes de lectura"
- Descripción: marketplace moderado para publicar libros con fotos y filtros, coordinar por chat y unirse a comunidades. Nota: la app NO procesa pagos — se elimina "envíos seguros y catálogo verificado" (falso).
- Capacidades: 1) Publicar libros con fotos, precios y filtros por categoría y estado · 2) Chat directo comprador–vendedor y calculadora de envíos · 3) Clubes de lectura públicos/privados con muro y valoraciones.

**Suti** (finanzas personales, React Native + Supabase)
- Tagline: "Tus gastos y tu saldo, bajo control — solo o en grupo"
- Descripción: fondos con saldo que se descuenta en tiempo real, gastos por categorías (comida, transporte, diversión…), gastos compartidos con división Tú/Ellos, historial por día/mes y gráficos de balance.
- Eliminar las capacidades actuales que NO existen en el código: "presupuestos mensuales", "metas de ahorro", "alertas proactivas".
- Capacidades: 1) Fondos con saldo disponible que se descuenta en tiempo real · 2) Gastos por categorías con historial por día o mes y gráficos de balance · 3) Gastos compartidos con contactos y división de porcentajes con notificaciones.

**CivilCardex** (plataforma WEB de ingeniería civil, React + Supabase)
- Badge: "SaaS • B2B" → "Plataforma Web • B2B" (no es app móvil; requiere tablet/PC)
- Tagline: "Diseño Hidrosanitario y Presupuestos de Obra" (los dos módulos reales: CivilFlow y Civil Manager)
- Descripción: diseño de redes sobre planos cargados, verificación normativa automática (IPC/UPC, NFPA, NTC, NSR-10, RAS 2000), isometrías, memorias de cálculo y presupuestos con APU.
- Eliminar capacidades falsas: "seguimiento predictivo de costos", "bitácora técnica digital", "supervisión de cuadrillas y maquinaria en faena".
- Capacidades: 1) Dibujo de redes de agua, sanitaria, lluvias, gas e incendio sobre tus planos · 2) Verificación normativa automática con isometrías y memorias de cálculo exportables · 3) Presupuestos y APU con catálogos de insumos, equipos y cuadrillas.

Verificación final: build de producción + revisión en navegador del acordeón expandido.