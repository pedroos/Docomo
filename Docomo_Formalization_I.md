<h1>DOCOMO</h1>

## FORMALIZATION I

Definitions

<ol>
    <li>Paragraphs
        <ul>
            <li>A paragraph is a sequence of sentences laid out contiguously (i.e. horizontally)</li>
            <li>Each paragraph is separated from another paragraph by significant vertical whitespace</li>
            <li>Every paragraph in one common documental resource shall belong to a single organizational structure such that the following holds:
                <ul>
                    <li>The organizational structure contains a relation, named "parenthood", that includes all paragraphs in the documental resource
                    <li>Under such a relation, each paragraph is related to exactly one other block of text which is said to be its parent
                    <li>Every documental resource contains a single paragraph that is parentless, termed a 'title'
                        <ul>
                            <li>Pertaining to this point, if a title is not present, an implicit title is assumed</li>
                        </ul>
                    </li>
                </ul>
            </li>
            <li>Every paragraph shall be distinguished from its parent paragraph by horizontal identation or horizontal whitespace</li>
        </ul>
    </li>
    <li>Blocks of text
        <ul>
            <li>A block of text is a sequence of paragraphs with a common parent paragraph</li>
            <li>A block of text with respect to ordering may be ordered or unordered</li>
            <li>An unordered block of text is a set of paragraphs with interchangeable disposition that doesn't alter its meaning
            <li>An ordered block of text is a sequence of paragraphs with a disposition that is revelant for its meaning</li>
        </ul>
    </li>
    <li>Identification: digital
        <ul>
            <li>Each documental resource defines, explicitly or implicitly (such as, for example, by inheritance), a set of separator digits</li>
            <li>A paragraph may be identified by a unique identifier that is a sequence of digits from a symbol set, such as the set of numbers or letters from a particular alphabet or character set, separated by one separator digit</li>
            <li>A separator digit is not part of an identifier, but only used in the presentation of a documental resource</li>
            <li>Each sequence of digits forming each identifier shall be unique in a single documental resource; that is, no two identifiers in a documental resource shall contain the same choice and order of digits (excluding separator digits)</li>
            <li>A separator digit as defined in one documental resource may not be used as a non-separator digit</li>
        </ul>
    </li>
    <li>Identification: symbolic
        <ul>
            <li>In case the definition in paragraph 3 produces an ambiguity, the definition in this paragraph shall override it</li>
            <li>A paragraph may be identified by a unique identifier that is a symbol or arrangement of symbols from a symbol set, such as the set of numbers or letters from a particular alphabet or character set</li>
            <li>Such an arrangement of symbols in one identifier shall be unique with respect to choice and ordering of symbols as occuring in a single documental resource</li>
        </ul>
    </li>
</ol>