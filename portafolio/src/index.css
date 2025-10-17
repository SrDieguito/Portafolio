import React from "react";
import { motion } from "framer-motion";

export default function Portfolio() {
  const fadeUp = {
    hidden: { opacity: 0, y: 20 },
    visible: { opacity: 1, y: 0 }
  };

  const stagger = {
    hidden: {},
    visible: { transition: { staggerChildren: 0.15 } }
  };

  return (
    <main className="min-h-screen bg-gradient-to-b from-white via-slate-50 to-slate-100 text-slate-900">
      <div className="max-w-5xl mx-auto px-6 py-12">

        {/* Header */}
        <motion.header 
          className="flex items-center justify-between mb-8"
          initial="hidden"
          animate="visible"
          variants={stagger}
        >
          <motion.div className="flex items-center gap-4" variants={fadeUp}>
            <motion.div
              className="w-16 h-16 bg-slate-200 rounded-full overflow-hidden flex items-center justify-center"
              initial={{ scale: 0 }}
              animate={{ scale: 1 }}
              transition={{ type: "spring", stiffness: 200, damping: 15 }}
            >
              <span className="text-slate-500">Foto</span>
            </motion.div>
            <div>
              <h1 className="text-2xl font-semibold text-slate-800">Diego Ernesto Santana Ramírez</h1>
              <p className="text-sm text-slate-500">Desarrollador Frontend • Full‑stack ligero</p>
            </div>
          </motion.div>

          <nav className="hidden md:flex gap-6 text-sm text-slate-600">
            {["Sobre mí", "Proyectos", "Habilidades", "Contacto"].map((link) => (
              <motion.a
                key={link}
                href={`#${link.toLowerCase().replace(" ", "")}`}
                className="hover:text-slate-800"
                whileHover={{ y: -3, scale: 1.05 }}
                transition={{ type: "spring", stiffness: 300 }}
              >
                {link}
              </motion.a>
            ))}
          </nav>
        </motion.header>

        {/* Hero */}
        <section className="grid md:grid-cols-2 gap-8 items-center mb-12">
          <motion.div
            variants={stagger}
            initial="hidden"
            animate="visible"
          >
            <motion.h2 
              className="text-3xl md:text-4xl font-extrabold text-slate-900 leading-tight" 
              variants={fadeUp}
            >
              Diseño y desarrollo de interfaces limpias y rápidas
            </motion.h2>
            <motion.p className="mt-4 text-slate-600" variants={fadeUp}>
              Egresado de Ingeniería en Sistemas (UTM). Principalmente enfocado en frontend con experiencia en backend, bases de datos y APIs. Me apasiona crear aplicaciones web complejas con interfaces limpias y accesibles.
            </motion.p>

            <motion.ul className="mt-6 grid grid-cols-1 sm:grid-cols-2 gap-2 text-sm text-slate-700" variants={stagger}>
              {[
                "📍 Cuenca, Ecuador",
                "📧 SrDieguit@gmail.com",
                "📱 0967038373",
                "🌐 Portafolio actual",
                "💻 GitHub: @SrDieguito"
              ].map((item, i) => (
                <motion.li key={i} variants={fadeUp}>
                  {i === 1 ? <a href="mailto:SrDieguit@gmail.com" className="underline">{item}</a> : item}
                </motion.li>
              ))}
            </motion.ul>

            <motion.div className="mt-6 flex items-center gap-3" variants={fadeUp}>
              <motion.a
                href="#projects"
                className="inline-flex items-center gap-2 bg-sky-600 hover:bg-sky-700 text-white px-4 py-2 rounded-md shadow"
                whileHover={{ scale: 1.05 }}
                transition={{ type: "spring", stiffness: 300 }}
              >
                Ver proyectos
              </motion.a>
              <motion.a
                href="/Diego_Santana_CV.pdf"
                className="inline-flex items-center gap-2 border border-slate-200 px-4 py-2 rounded-md text-slate-700"
                whileHover={{ scale: 1.05 }}
                transition={{ type: "spring", stiffness: 300 }}
              >
                Descargar CV
              </motion.a>
            </motion.div>
          </motion.div>

          <motion.div
            className="relative w-full h-64 md:h-72 bg-gradient-to-br from-sky-50 to-white rounded-2xl shadow-lg flex items-center justify-center"
            initial={{ scale: 0.98, opacity: 0 }}
            animate={{ scale: 1, opacity: 1 }}
            transition={{ duration: 0.6, delay: 0.1 }}
          >
            <div className="absolute -left-8 -top-8 w-40 h-40 bg-sky-100 rounded-xl opacity-70 blur-md"></div>
            <div className="absolute -right-6 bottom-0 w-32 h-32 bg-slate-100 rounded-xl opacity-80 blur-sm"></div>
            <div className="w-44 h-44 bg-slate-200 rounded-lg flex items-center justify-center">Imagen o mockup</div>
          </motion.div>
        </section>

        {/* About */}
        <section id="about" className="mb-10">
          <motion.h3 className="text-xl font-semibold text-slate-800" variants={fadeUp}>Sobre mí</motion.h3>
          <motion.p className="mt-3 text-slate-600" variants={fadeUp}>
            Soy egresado en Ingeniería en Sistemas de la Universidad Técnica de Manabí. Tengo 23 años y me especializo en desarrollo frontend, aunque también trabajo con backend, gestión de bases de datos y soluciones integrales. Disfruto resolver problemas complejos y optimizar la experiencia del usuario con tecnologías modernas como React, Next.js, Tailwind CSS y Node.js.
          </motion.p>

          <motion.div className="mt-6 grid md:grid-cols-3 gap-4" variants={stagger}>
            {[
              { title: "Educación", content: "Ingeniería en Sistemas de Información — Universidad Técnica de Manabí (Noviembre 2020 – Presente). Tesis en desarrollo." },
              { title: "Experiencia", content: "Prácticas y proyectos en Innovatech (INNOVA UTM): desarrollo de aplicaciones web, integración con IA y gestión de datos." },
              { title: "Idiomas", content: "Español (nativo) • Inglés (básico)" }
            ].map((item, i) => (
              <motion.div key={i} className="p-4 bg-white rounded-xl shadow-sm" variants={fadeUp}>
                <h4 className="font-medium text-slate-800">{item.title}</h4>
                <p className="text-sm text-slate-600 mt-2">{item.content}</p>
              </motion.div>
            ))}
          </motion.div>
        </section>

        {/* Projects */}
        <section id="projects" className="mb-12">
          <motion.h3 className="text-xl font-semibold text-slate-800" variants={fadeUp}>Proyectos destacados</motion.h3>
          <div className="mt-6 flex flex-col gap-6">
            {[
              { title: "INNOVATECH", description: "Plataforma tipo aula invertida con algoritmos de recomendación, integración con APIs de IA, roles de usuario, cálculo automático de notas y una interfaz pulida.", tech: "React, Next.js, Node.js, PostgreSQL, Tailwind CSS, Vercel", github: "https://github.com/SrDieguito/Innovatech", demo: "https://innovatech.vercel.app/" },
              { title: "BETESDA", description: "Sitio estático informativo para una iglesia, con inserción dinámica de videos desde YouTube y contenido administrable.", tech: "HTML, CSS, JavaScript", github: "https://github.com/SrDieguito/Betesda", demo: "https://betesda.vercel.app/" },
              { title: "INNOVA (UTM)", description: "Aplicación para el registro de estudiantes en eventos universitarios, desarrollada para la UTM. Manejo de datos y roles administrativos.", tech: "PHP, MySQL, Bootstrap", github: "https://github.com/SrDieguito/Innova" }
            ].map((proj, i) => (
              <motion.article key={i}
                className="p-4 bg-white rounded-xl shadow-sm hover:shadow-md transition-shadow"
                whileHover={{ y: -6, scale: 1.02 }}
                whileInView={{ opacity: [0, 1], y: [20, 0] }}
                viewport={{ once: true }}
                transition={{ duration: 0.5 }}
              >
                <h4 className="font-semibold">{proj.title}</h4>
                <p className="text-sm text-slate-600 mt-2">{proj.description}</p>
                <p className="mt-3 text-xs text-slate-500">Tecnologías: {proj.tech}</p>
                <div className="mt-3 flex gap-2">
                  <a className="text-sm underline text-sky-600" href={proj.github} target="_blank">Ver código</a>
                  {proj.demo && <a className="text-sm underline text-sky-600" href={proj.demo} target="_blank">Ver demo</a>}
                </div>
              </motion.article>
            ))}
          </div>
        </section>

        {/* Skills */}
        <section id="skills" className="mb-12">
          <motion.h3 className="text-xl font-semibold text-slate-800" variants={fadeUp}>Habilidades</motion.h3>
          <motion.div className="mt-4 grid sm:grid-cols-2 gap-4" variants={stagger}>
            {[
              { title: "Lenguajes", content: "JavaScript, Python, PHP" },
              { title: "Frameworks / Tools", content: "React, Next.js, Node.js, Tailwind CSS, Git, Vercel, Railway" },
              { title: "Bases de datos", content: "MySQL, PostgreSQL" },
              { title: "Herramientas", content: "VS Code, Docker, DBeaver, GitHub" }
            ].map((skill, i) => (
              <motion.div key={i} className="p-4 bg-white rounded-xl shadow-sm" variants={fadeUp}>
                <h5 className="font-medium">{skill.title}</h5>
                <p className="text-sm text-slate-600 mt-2">{skill.content}</p>
              </motion.div>
            ))}
          </motion.div>
        </section>

        {/* Contact */}
        <section id="contact" className="mb-16">
          <motion.h3 className="text-xl font-semibold text-slate-800" variants={fadeUp}>Contacto</motion.h3>
          <motion.div className="mt-4 grid md:grid-cols-2 gap-6 items-start" variants={stagger}>
            <motion.div className="p-6 bg-white rounded-xl shadow-sm" variants={fadeUp}>
              <p className="text-sm text-slate-600">¿Quieres trabajar conmigo o tienes una idea? Escríbeme:</p>
              <p className="mt-3 font-medium">📧 <a href="mailto:SrDieguit@gmail.com" className="underline">SrDieguit@gmail.com</a></p>
              <p className="mt-1">📱 0967038373</p>
              <p className="mt-3 text-xs text-slate-500">También puedes revisar mi código en <a href="https://github.com/SrDieguito?tab=repositories" target="_blank" className="underline">GitHub</a> o ver demos en mi portafolio.</p>
            </motion.div>

            <motion.form className="p-6 bg-white rounded-xl shadow-sm flex flex-col gap-3" variants={fadeUp}>
              <input className="border border-slate-200 p-2 rounded" placeholder="Nombre" />
              <input className="border border-slate-200 p-2 rounded" placeholder="Correo" />
              <textarea className="border border-slate-200 p-2 rounded h-24" placeholder="Mensaje"></textarea>
              <button className="bg-sky-600 hover:bg-sky-700 text-white px-4 py-2 rounded">Enviar mensaje</button>
            </motion.form>
          </motion.div>
        </section>

        {/* Footer */}
        <motion.footer
          className="text-center text-xs text-slate-400 py-6"
          initial={{ y: 20, opacity: 0 }}
          whileInView={{ y: 0, opacity: 1 }}
          viewport={{ once: true }}
          transition={{ duration: 0.6 }}
        >
          © {new Date().getFullYear()} Diego Ernesto Santana Ramírez — Cuenca, Ecuador
        </motion.footer>

      </div>
    </main>
  );
}
