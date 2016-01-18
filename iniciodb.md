

--
-- Base de datos: `Aguila`
--

-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `estado`
--

CREATE TABLE IF NOT EXISTS `estado` (
  `id_estado` int(11) NOT NULL AUTO_INCREMENT,
  `estado` text NOT NULL,
  PRIMARY KEY (`id_estado`)
) ENGINE=MyISAM DEFAULT CHARSET=latin1 AUTO_INCREMENT=1 ;

--
--
--


-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `municipio`
--

CREATE TABLE IF NOT EXISTS `municipio` (
  `id_municipio` int(11) NOT NULL AUTO_INCREMENT,
  `municipio` text NOT NULL,
  PRIMARY KEY (`id_municipio`)
) ENGINE=MyISAM DEFAULT CHARSET=latin1 AUTO_INCREMENT=1 ;

--

--


-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `pais`
--

CREATE TABLE IF NOT EXISTS `pais` (
  `id_pais` int(11) NOT NULL AUTO_INCREMENT,
  `pais` text NOT NULL,
  PRIMARY KEY (`id_pais`)
) ENGINE=MyISAM DEFAULT CHARSET=latin1 AUTO_INCREMENT=1 ;

--
-- Volcar la base de datos para la tabla `pais`
--


-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `persona`
--

CREATE TABLE IF NOT EXISTS `persona` (
  `id_persona` int(11) NOT NULL,
  `nombre` text NOT NULL,
  `appat` text NOT NULL,
  `apmat` text NOT NULL,
  `edad` int(11) NOT NULL,
  `telefono` int(11) NOT NULL,
  PRIMARY KEY (`id_persona`)
) ENGINE=MyISAM DEFAULT CHARSET=latin1;

--

--

