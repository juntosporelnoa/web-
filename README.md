                en: {
                    translation: {
                        title: "Energy Proposal",
                        subtitle: "Resource unification for sustainable development and revenue generation.",
                        intro_title: "Introduction",
                        intro_text: "The provinces of Salta, Jujuy, and Tucumán propose a strategic collaboration to harness their energy and mineral resources. The goal is to build an energy storage plant to export surpluses to neighboring countries.",
                        images_section: "Project Images",
                        comments_section: "Comments",
                        s_section: "Jujuy",
                        tom_lithium: "Annual extraction of 17,500 tons of lithium.",
                        e_income: "Expected annual income: $198,625,000.",
                        f_projects: "Ongoing projects: export to Japan and China, network improvements for distribution.",
                        salta_section: "Salta",
                        salta_solar: "Solar, wind, and hydroelectric energy production.",
                        salta_recommendations: "Recommended projects: Los Colorado Solar Park (100 MW), Cabra Corral Hydro Plant (120 MW).",
                        salta_lithium: "Potential to generate $88 million in income from lithium exports.",
                        tucuman_section: "Tucumán",
                        tucuman_generation: "Hydroelectric, solar, and thermal energy generation.",
                        tucuman_financing: "Financing management through taxes on leading companies in the sector.",
                        tucuman_capacity: "Installed capacity: 7596 GWh, with surplus of 4766 GWh.",
                        conclusion_section: "Conclusion",
                        conclusion_text: "The collaboration between these three provinces will enable sustainable economic development and position the region as a leader in renewable energy exports.",
                        footer_text: "Proposal created by the delegations of Salta, Jujuy, and Tucumán. &copy; 2024",
                    }
                }
            }
        }, function(err, t) {
            // Cambiar texto después de la inicialización
            changeLanguage('es');
        });

        // Configurar cambio de idioma
        document.querySelectorAll('#language-switch button').forEach(function(button) {
            button.addEventListener('click', function() {
                var language = button.getAttribute('data-lang');
                changeLanguage(language);
            });
        });
    </script>
</body>
</html>
