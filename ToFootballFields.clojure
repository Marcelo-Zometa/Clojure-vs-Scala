;This program converts an object's length given in meters to football fields


;Function for converting the measures
(defn math [length football obj] (def result (/ length football))
             (println (str obj " is " result " football fields long!")))

;Driver function
(defn main []

    (def footballField 109.7)
    (println "Welcome. This program will tell you the length of a thing but measured in football fields.\n")

    (println "So, what do you want to measure?")
    (def myObj (read-line))

    (println (str "What is the length of " myObj " in meters?"))
    (def myLength (read))

    ;Calling of math function
    (math myLength footballField myObj)
)

;Calling of main function
(main)
