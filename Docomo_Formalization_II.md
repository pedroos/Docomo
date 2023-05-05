<h1>DOCOMO</h1>

## FORMALIZATION II

Definitions

  - Elements
    - An element is the smallest indivisible unit of a documental resource
    - The following elements are defined:
      - Paragraph
  - Types
    - A type is a name common to distinct elements
    - The following types are defined:
      - Documental resource
      - Sentence
      - Paragraph
      - Relation
      - Block of text
      - Identifier
      - Digit
      - Symbol
  - Properties
    - A property is a proposition which is defined for a type or set of types, and which is asserted to be true for 
      particular elements of such type
      - Each property is notated with the prefix "Is"
    - The following properties table containing properties and associated types is defined:
        <table>
            <tr>
                <th>Property</th>
                <th>Defined types</th>
            </tr>
            <tr>
                <td>IsParent</td>
                <td>Paragraph</td>
            </tr>
            <tr>
                <td>IsTitle</td>
                <td>Paragraph</td>
            </tr>
            <tr>
                <td>IsOrdered</td>
                <td>Block of text</td>
            </tr>
            <tr>
                <td>IsSeparator</td>
                <td>Digit</td>
            </tr>
        </table>