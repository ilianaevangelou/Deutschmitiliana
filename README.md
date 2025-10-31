# Deutschmitiliana
git init git add . git commit -m "Initial commit" git branch -M main git remote add origin https://github.com/DEINNAME/deutsch-mit-iliana.git git push -u origin main
      <p className="text-2xl text-muted-foreground italic">
        Μάθε γερμανικά με διασκεδαστικό τρόπο!
      </p>

      <p className="text-2xl text-primary font-semibold">
        Lerne Deutsch mit Spaß und tollen Aufgaben
      </p>

      <p className="text-xl text-muted-foreground italic">
        Μάθε γερμανικά με διασκέδαση και υπέροχες ασκήσεις
      </p>6

      <p className="text-lg leading-relaxed max-w-xl text-gray-700">
        Interaktive Übungen, Vokabeltrainer und Spiele für Schüler von 9–15
        Jahren. Lerne neue Wörter, bilde Sätze und teste dein Wissen mit
        spannenden Aufgaben!
      </p>

      <button
        type="button"
        className="mt-4 px-6 py-3 bg-primary text-white rounded-xl shadow-md hover:bg-primary/90 transition-transform duration-200 hover:scale-105"
      >
        Jetzt starten 🚀
      </button>
    </div>

    {/* Bildbereich */}
    <div className="flex justify-center">
      <img
        src="/images/learning-german.svg"
        alt="Lernende Kinder"
        className="w-full max-w-md drop-shadow-lg"
        loading="lazy"
      />
    </div>
  </section>

  {/* Aufgaben-Sektion */}
  <section className="py-20 px-6 bg-white">
    <h2 className="text-3xl font-bold text-center mb-10 text-primary">
      Interaktive Aufgaben
    </h2>

    <div className="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
      {/* Aufgabe 1 */}
      <div className="p-6 bg-blue-50 rounded-2xl shadow hover:shadow-lg transition">
        <h3 className="text-xl font-semibold mb-2">🧩 Wortschatz-Spiel</h3>
        <p className="text-gray-600 mb-4">
          Finde die richtigen Übersetzungen und lerne spielerisch neue
          Wörter.
        </p>
        <button className="px-4 py-2 bg-primary text-white rounded-lg hover:bg-primary/90">
          Jetzt spielen
        </button>
      </div>

      {/* Aufgabe 2 */}
      <div className="p-6 bg-yellow-50 rounded-2xl shadow hover:shadow-lg transition">
        <h3 className="text-xl font-semibold mb-2">✍️ Satzbau</h3>
        <p className="text-gray-600 mb-4">
          Ordne die Wörter richtig und bilde korrekte deutsche Sätze.
        </p>
        <button className="px-4 py-2 bg-primary text-white rounded-lg hover:bg-primary/90">
          Aufgabe starten
        </button>
      </div>

      {/* Aufgabe 3 */}
      <div className="p-6 bg-green-50 rounded-2xl shadow hover:shadow-lg transition">
        <h3 className="text-xl font-semibold mb-2">🎧 Hörverständnis</h3>
        <p className="text-gray-600 mb-4">
          Höre kurze Dialoge und beantworte Fragen dazu.
        </p>
        <button className="px-4 py-2 bg-primary text-white rounded-lg hover:bg-primary/90">
          Los geht’s
        </button>
      </div>
    </div>
  </section>

  {/* Footer */}
  <footer className="bg-gray-900 text-white py-8 text-center">
    <p className="text-lg font-medium">
      © {new Date().getFullYear()} Deutsch mit Iliana. Alle Rechte
      vorbehalten.
    </p>
  </footer>
</main>
