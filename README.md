# 🌿 DrYeska - Educational Candy Crush Game

Un juego tipo Candy Crush con temática educativa sobre plantas de cannabis. Gana puntos jugando y úsalos para comprar tarjetas educativas con datos interesantes sobre la planta.

## 🎮 Características

### Fase 1: Core del Juego
- ✅ Mecánica de match-3 (arrastra y suelta fichas)
- ✅ Sistema de puntos dinámico
- ✅ Niveles progresivos con dificultad
- ✅ Guardado de datos del jugador
- ✅ Interfaz responsiva

### Fase 2: Sistema de Tienda
- 🛍️ Tienda de tarjetas educativas
- 💳 Compra con puntos ganados
- 📚 Inventario y galería de colección
- 🌟 Tarjetas raras y especiales
- 📊 Sistema de logros y estadísticas

### Fase 3: Contenido Educativo
- 📖 50+ tarjetas iniciales
- 🌱 Información sobre variedades (Sativa, Indica, Híbridas)
- 🧬 Componentes (THC, CBD, terpenos)
- 📜 Historia y cultivo
- 🔬 Datos científicos y curiosos

## 🛠️ Stack Tecnológico

- **Framework de Juego**: Phaser 3
- **Lenguaje**: JavaScript / ES6+
- **Frontend**: HTML5, CSS3
- **Almacenamiento**: LocalStorage (fase 1), Firebase (producción)
- **Diseño**: Responsive design

## 📁 Estructura del Proyecto

```
DrYeska/
├── src/
│   ├── scenes/
│   │   ├── BootScene.js          # Carga de assets
│   │   ├── MenuScene.js          # Pantalla principal
│   │   ├── GameScene.js          # Lógica del juego match-3
│   │   ├── GameOverScene.js      # Fin del nivel
│   │   └── ShopScene.js          # Tienda de tarjetas
│   ├── entities/
│   │   ├── Tile.js               # Ficha del tablero
│   │   ├── Board.js              # Lógica del tablero
│   │   └── Card.js               # Tarjeta educativa
│   ├── systems/
│   │   ├── PointsSystem.js       # Gestión de puntos
│   │   ├── ScoreCalculator.js    # Cálculo de puntos
│   │   ├── StorageManager.js     # Guardado de datos
│   │   └── SoundManager.js       # Gestión de sonidos
│   ├── data/
│   │   ├── cards.js              # Base de tarjetas educativas
│   │   ├── levels.js             # Configuración de niveles
│   │   └── gameConfig.js         # Configuración global
│   ├── assets/
│   │   ├── images/
│   │   │   ├── tiles/            # Sprites de fichas
│   │   │   ├── ui/               # Botones, barras, fondos
│   │   │   └── cards/            # Imágenes de tarjetas
│   │   ├── sounds/
│   │   │   ├── match.mp3
│   │   │   ├── levelup.mp3
│   │   │   └── purchase.mp3
│   │   └── fonts/
│   └── main.js                   # Punto de entrada Phaser
├── index.html                    # HTML principal
├── style.css                     # Estilos globales
├── package.json                  # Dependencias
├── .gitignore                    # Archivos a ignorar
└── docs/
    ├── ARCHITECTURE.md           # Detalles técnicos
    ├── GAMEPLAY.md               # Mecánicas del juego
    └── CARDS.md                  # Guía de tarjetas educativas
```

## 🚀 Roadmap de Desarrollo

### Semana 1-2: Core Gameplay
- [ ] Configurar Phaser 3 y estructura base
- [ ] Implementar tablero match-3 (8x8)
- [ ] Mecánica de arrastra y suelta
- [ ] Detección de matches horizontales/verticales
- [ ] Sistema de puntos básico
- [ ] Menú principal y selección de nivel

### Semana 3: Sistema de Tienda
- [ ] Interfaz de tienda
- [ ] Base de datos de 50+ tarjetas
- [ ] Sistema de compra con puntos
- [ ] Inventario del jugador
- [ ] Galería de colección
- [ ] Tarjetas raras (rareza: común, poco común, rara, épica, legendaria)

### Semana 4: Pulido y Extras
- [ ] Sistema de logros
- [ ] Sonidos y música
- [ ] Animaciones mejoradas
- [ ] Guardado en la nube (Firebase)
- [ ] Estadísticas y rankings
- [ ] Tema visual pulido

## 🎯 Mecánicas del Juego

### Sistema de Puntos
```
- Partida completada: 100 puntos base
- Combo x2: +50% puntos
- Combo x3+: +100% puntos
- Tarjeta rara encontrada: +500 puntos
- Logro desbloqueado: +100 puntos
- Total acumulado sin límite
```

### Precio de Tarjetas
```
- Común: 50 puntos
- Poco común: 100 puntos
- Rara: 200 puntos
- Épica: 300 puntos
- Legendaria: 500 puntos
```

## 📚 Contenido Educativo (Ejemplos de Tarjetas)

### Categoría: Variedades
- Sativa - Efectos energizantes
- Indica - Efectos relajantes
- Híbrida - Equilibrio de ambos

### Categoría: Componentes
- THC - Tetrahidrocannabinol
- CBD - Cannabidiol
- Terpenos - Aromas y sabores

### Categoría: Historia
- Orígenes en Asia Central
- Usos medicinales antiguos
- Evolución moderna

### Categoría: Cultivo
- Ciclo de vida (germinación, vegetación, floración)
- Condiciones óptimas
- Plagas y prevención

## 💻 Instalación y Ejecución

### Requisitos
- Node.js 14+
- npm o yarn

### Pasos
```bash
# Clonar repositorio
git clone https://github.com/zexusrudux/DrYeska.git
cd DrYeska

# Instalar dependencias
npm install

# Ejecutar servidor de desarrollo
npm run dev

# Compilar para producción
npm run build
```

## 📖 Documentación Adicional

- [Arquitectura Técnica](docs/ARCHITECTURE.md)
- [Mecánicas de Juego](docs/GAMEPLAY.md)
- [Base de Tarjetas](docs/CARDS.md)

## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo licencia MIT.

## 👨‍💻 Autor

- **zexusrudux** - Desarrollo principal

## 📞 Contacto

Para preguntas o sugerencias, abre un issue en GitHub.

---

**Estado del Proyecto**: 🔨 En Desarrollo (Fase 1)
**Última Actualización**: 2026-09-10
