type Developer struct {
    Name      string
    Company   string
    Language  string
    Databases []string
    Builds    []string
}

var fahriddin = Developer{
    Name:      "Fahriddin Rakhimberdiev",
    Company:   "Udevs",
    Language:  "Go",
    Databases: []string{"PostgreSQL", "MySQL", "Redis"},
    Builds:    []string{"Monoliths", "Microservices"},
}
